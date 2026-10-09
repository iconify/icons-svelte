<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbmpiqbiz.css';
import '../../css/r/rcdbnd-dt.css';
import '../../css/w/wbtogqaxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nbmpiqbiz"/><path class="rcdbnd-dt"/><path class="wbtogqaxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-exchanger-48-bold" {...props}></Icon>
