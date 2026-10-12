<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oanunl3eu.css';
import '../../css/l/l42y8cc0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oanunl3eu"/><path class="l42y8cc0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:location-stroke-20" {...props}></Icon>
