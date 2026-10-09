<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ws95bmc.css';
import '../../css/g/gtwn_2b4z.css';
import '../../css/l/lsfhf11ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e6ws95bmc"/><path class="gtwn_2b4z"/><path class="lsfhf11ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meeting-48" {...props}></Icon>
