<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9x2wm1fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y9x2wm1fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:apple" {...props}></Icon>
