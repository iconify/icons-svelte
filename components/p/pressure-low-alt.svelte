<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_1etb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1_1etb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:pressure-low-alt" {...props}></Icon>
