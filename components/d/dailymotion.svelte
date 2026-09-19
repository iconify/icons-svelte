<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1vt4ejsn.css';
import '../../css/w/wig593f0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1vt4ejsn"/><path class="wig593f0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:dailymotion" {...props}></Icon>
