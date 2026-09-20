<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxh_3bcls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxh_3bcls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:panorama-horizontal-filled" {...props}></Icon>
