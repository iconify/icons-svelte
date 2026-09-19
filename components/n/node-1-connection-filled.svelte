<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s98hn0ejv.css';
import '../../css/j/jm9p9sjox.css';
import '../../css/s/sololpbna.css';
import '../../css/w/wphbtcjgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s98hn0ejv"/><path clip-rule="evenodd" class="jm9p9sjox"/><circle class="sololpbna"/><path clip-rule="evenodd" class="wphbtcjgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:node-1-connection-filled" {...props}></Icon>
