<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs99ztb-t.css';
import '../../css/m/mcbwykhxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs99ztb-t"/><path class="mcbwykhxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:plane-ticket" {...props}></Icon>
