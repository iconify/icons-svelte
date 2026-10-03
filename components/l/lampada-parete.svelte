<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm_-1ibgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_-1ibgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lampada-parete" {...props}></Icon>
