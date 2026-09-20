<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy_mfkb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yy_mfkb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flag" {...props}></Icon>
