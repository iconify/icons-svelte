<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp-lybbkh.css';
import '../../css/u/unvddzmln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zp-lybbkh"/><path class="unvddzmln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:doorbell-20" {...props}></Icon>
