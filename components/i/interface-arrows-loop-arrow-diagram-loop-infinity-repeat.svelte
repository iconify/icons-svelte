<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sda85vqfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sda85vqfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-loop-arrow-diagram-loop-infinity-repeat" {...props}></Icon>
