<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzephrjzr.css';
import '../../css/q/qpinueb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pzephrjzr"/><path class="qpinueb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-picture-polaroid" {...props}></Icon>
