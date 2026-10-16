<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv_yx13wf.css';
import '../../css/h/hh9nw1bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xv_yx13wf"/><path class="hh9nw1bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-schedule-48-bold" {...props}></Icon>
