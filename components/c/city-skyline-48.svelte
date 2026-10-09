<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyn0tjbsp.css';
import '../../css/f/f9-7d2bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wyn0tjbsp"/><path class="f9-7d2bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:city-skyline-48" {...props}></Icon>
