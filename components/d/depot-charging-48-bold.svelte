<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqu-jov0y.css';
import '../../css/i/i2hezybim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kqu-jov0y"/><path class="i2hezybim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:depot-charging-48-bold" {...props}></Icon>
