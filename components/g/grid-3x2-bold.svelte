<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/garh2ib3b.css';
import '../../css/l/l397zn2sl.css';
import '../../css/t/tmf0l99tw.css';
import '../../css/v/v51ggtl0s.css';
import '../../css/r/rwrpbcc9w.css';
import '../../css/f/f3wqpy6nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="garh2ib3b"/><path class="l397zn2sl"/><path class="tmf0l99tw"/><path class="v51ggtl0s"/><path class="rwrpbcc9w"/><path class="f3wqpy6nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x2-bold" {...props}></Icon>
