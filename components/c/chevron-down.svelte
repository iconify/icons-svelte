<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izq-akrqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="izq-akrqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-down" {...props}></Icon>
