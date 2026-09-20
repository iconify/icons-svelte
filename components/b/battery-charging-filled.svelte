<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeig_sbyw.css';
import '../../css/z/zvd_26b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeig_sbyw"/><path class="zvd_26b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:battery-charging-filled" {...props}></Icon>
