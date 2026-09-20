<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncrqd2_yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncrqd2_yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:extension-off" {...props}></Icon>
