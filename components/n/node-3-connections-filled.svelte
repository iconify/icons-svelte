<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s98hn0ejv.css';
import '../../css/t/tlit071fe.css';
import '../../css/i/ishbz4cce.css';
import '../../css/s/sololpbna.css';
import '../../css/r/rt617yb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s98hn0ejv"/><path clip-rule="evenodd" class="tlit071fe"/><circle class="ishbz4cce"/><circle class="sololpbna"/><circle class="rt617yb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:node-3-connections-filled" {...props}></Icon>
