<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt8wqvb9w.css';
import '../../css/f/ft8kw_b7z.css';
import '../../css/t/tfewnyb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kt8wqvb9w"/><path class="ft8kw_b7z"/><path class="tfewnyb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-recovery-48" {...props}></Icon>
