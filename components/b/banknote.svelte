<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy2lufbjs.css';
import '../../css/p/psqa162mc.css';
import '../../css/i/ipeafrb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy2lufbjs wm-k"/><path class="psqa162mc wm-a"/><path class="ipeafrb_f wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:banknote" {...props}></Icon>
