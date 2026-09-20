<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm5wywbws.css';
import '../../css/q/ql13oqt-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wm5wywbws"/><path class="ql13oqt-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:docked-left" {...props}></Icon>
