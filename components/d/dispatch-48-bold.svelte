<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5nrbcb_x.css';
import '../../css/p/px1uvz_dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5nrbcb_x"/><path class="px1uvz_dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dispatch-48-bold" {...props}></Icon>
