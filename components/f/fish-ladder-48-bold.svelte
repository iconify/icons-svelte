<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf7o7sb5z.css';
import '../../css/s/shn1ydbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gf7o7sb5z"/><path class="shn1ydbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-ladder-48-bold" {...props}></Icon>
