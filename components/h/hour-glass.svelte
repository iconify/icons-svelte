<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-n0b1j-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e-n0b1j-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:hour-glass" {...props}></Icon>
