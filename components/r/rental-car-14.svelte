<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr-7drb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kr-7drb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:rental-car-14" {...props}></Icon>
