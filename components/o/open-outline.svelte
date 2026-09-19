<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unwlo-bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unwlo-bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:open-outline" {...props}></Icon>
