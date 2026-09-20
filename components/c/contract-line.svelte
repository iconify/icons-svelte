<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n188czbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n188czbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contract-line" {...props}></Icon>
