<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffnde8cke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ffnde8cke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-lightning-48-bold" {...props}></Icon>
