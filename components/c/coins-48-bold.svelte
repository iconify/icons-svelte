<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ragurnetf.css';
import '../../css/p/pwh5jrbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ragurnetf"/><path class="pwh5jrbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coins-48-bold" {...props}></Icon>
