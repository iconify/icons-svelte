<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp9bowwdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tp9bowwdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:line" {...props}></Icon>
