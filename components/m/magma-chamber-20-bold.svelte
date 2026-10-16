<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5lwlib7c.css';
import '../../css/l/l6xpa5bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l5lwlib7c"/><path class="l6xpa5bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magma-chamber-20-bold" {...props}></Icon>
