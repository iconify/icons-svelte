<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egko-y1rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egko-y1rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edge-line" {...props}></Icon>
