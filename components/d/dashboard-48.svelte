<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-zbgc76c.css';
import '../../css/n/ny48sabtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f-zbgc76c"/><path class="ny48sabtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dashboard-48" {...props}></Icon>
