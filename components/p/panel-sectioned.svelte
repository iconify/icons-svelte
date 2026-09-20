<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2mpopbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="k2mpopbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:panel-sectioned" {...props}></Icon>
