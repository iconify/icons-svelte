<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8_cpacsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h8_cpacsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-crossover-up" {...props}></Icon>
