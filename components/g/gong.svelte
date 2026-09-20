<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpm3jpbta.css';
import '../../css/a/a4agvic7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":171.3,"height":60};
const content = `<path class="vpm3jpbta"/><path class="a4agvic7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gong" {...props}></Icon>
