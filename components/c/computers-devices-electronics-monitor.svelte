<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jegz6cbzd.css';
import '../../css/i/icmtrjuub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jegz6cbzd"/><path class="icmtrjuub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-monitor" {...props}></Icon>
