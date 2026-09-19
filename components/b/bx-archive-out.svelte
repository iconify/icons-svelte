<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwj-tdbmb.css';
import '../../css/x/xcy8lybpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwj-tdbmb"/><path class="xcy8lybpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-archive-out" {...props}></Icon>
