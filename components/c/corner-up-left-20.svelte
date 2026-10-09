<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-rr4hcr.css';
import '../../css/t/tjeffabft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iq-rr4hcr"/><path class="tjeffabft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-up-left-20" {...props}></Icon>
