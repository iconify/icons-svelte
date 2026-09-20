<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av_0phb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av_0phb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:full-screen-maximize" {...props}></Icon>
