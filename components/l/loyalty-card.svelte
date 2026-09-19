<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qms-c1bqk.css';
import '../../css/l/lpwhomvqt.css';
import '../../css/k/kvmx2ccby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qms-c1bqk"/><path class="lpwhomvqt"/><path class="kvmx2ccby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:loyalty-card" {...props}></Icon>
