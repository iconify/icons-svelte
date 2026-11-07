<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osczg8bol.css';
import '../../css/b/bnsx8gbka.css';
import '../../css/y/yb1t-pwor.css';
import '../../css/o/ogh4q1bay.css';
import '../../css/s/s6qd-zbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osczg8bol"/><path class="bnsx8gbka"/><path class="yb1t-pwor"/><path class="ogh4q1bay"/><path class="s6qd-zbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-send-bold-duotone" {...props}></Icon>
