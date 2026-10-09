<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrsls2auw.css';
import '../../css/f/fapgrnb1n.css';
import '../../css/l/l9gndm50e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nrsls2auw"/><path class="fapgrnb1n"/><path class="l9gndm50e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bird-safe-48-bold" {...props}></Icon>
