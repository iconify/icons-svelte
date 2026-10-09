<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tderinysh.css';
import '../../css/v/ve1blyb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tderinysh"/><path class="ve1blyb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kettle-48" {...props}></Icon>
