<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg0vzvbzz.css';
import '../../css/r/r2tsl51tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vg0vzvbzz"/><path class="r2tsl51tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:newspaper-48" {...props}></Icon>
