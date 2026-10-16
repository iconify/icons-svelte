<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js4ro1b0l.css';
import '../../css/y/y-afnmd_s.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="js4ro1b0l"/><path class="y-afnmd_s"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-battery-alert-48" {...props}></Icon>
