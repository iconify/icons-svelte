<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhgf1rbxc.css';
import '../../css/c/c3af0we0f.css';
import '../../css/s/sdpc00hnc.css';
import '../../css/b/bk2l0-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhgf1rbxc wm-k"/><path class="c3af0we0f wm-k"/><path class="sdpc00hnc wm-s"/><path class="bk2l0-b2l wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:phone-call" {...props}></Icon>
