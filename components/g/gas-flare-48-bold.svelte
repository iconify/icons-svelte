<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgcs14bkt.css';
import '../../css/o/o2vuw7npi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fgcs14bkt"/><path class="o2vuw7npi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-flare-48-bold" {...props}></Icon>
