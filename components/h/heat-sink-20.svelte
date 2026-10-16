<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci9il8bto.css';
import '../../css/n/np35iacps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ci9il8bto"/><path class="np35iacps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-sink-20" {...props}></Icon>
