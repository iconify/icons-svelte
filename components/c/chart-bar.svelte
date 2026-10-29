<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onlbud-6m.css';
import '../../css/z/z3dt8qrmb.css';
import '../../css/l/ljw94hbdi.css';
import '../../css/m/mn_fpfo9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onlbud-6m wm-k"/><path class="wm-k z3dt8qrmb"/><path class="ljw94hbdi wm-k"/><path class="mn_fpfo9f wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chart-bar" {...props}></Icon>
