<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d464e6b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d464e6b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-expand" {...props}></Icon>
