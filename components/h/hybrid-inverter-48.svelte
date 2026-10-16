<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgp2dhbyi.css';
import '../../css/e/eeyhvjk3w.css';
import '../../css/b/bzc7nkboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wgp2dhbyi"/><path class="eeyhvjk3w"/><path class="bzc7nkboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hybrid-inverter-48" {...props}></Icon>
