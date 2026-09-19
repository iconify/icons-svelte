<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn_e35btc.css';
import '../../css/v/vtfwic-qn.css';
import '../../css/u/uqlamj4tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn_e35btc"/><path class="vtfwic-qn"/><circle class="uqlamj4tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:hard-drive-outline" {...props}></Icon>
