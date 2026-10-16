<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ala7sfbdm.css';
import '../../css/t/tl7j9h2ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ala7sfbdm"/><path class="tl7j9h2ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rain-gauge-20-bold" {...props}></Icon>
