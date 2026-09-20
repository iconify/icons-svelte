<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k85kx3bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k85kx3bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloud-download" {...props}></Icon>
