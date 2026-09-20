<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0xlczgvc.css';
import '../../css/s/syzigfb3q.css';
import '../../css/j/j_a6aebui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0xlczgvc"/><path class="syzigfb3q"/><path class="j_a6aebui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monero" {...props}></Icon>
