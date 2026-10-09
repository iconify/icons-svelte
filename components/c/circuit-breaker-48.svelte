<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-8xbcar.css';
import '../../css/s/sw1rf8b4b.css';
import '../../css/b/b3fhqxbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mp-8xbcar"/><path class="sw1rf8b4b"/><path class="b3fhqxbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circuit-breaker-48" {...props}></Icon>
