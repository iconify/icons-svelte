<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfiie8bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yfiie8bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gitkraken" {...props}></Icon>
