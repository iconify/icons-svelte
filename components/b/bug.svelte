<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aif5mxb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="aif5mxb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:bug" {...props}></Icon>
