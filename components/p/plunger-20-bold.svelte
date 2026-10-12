<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibm1vrbdc.css';
import '../../css/k/k_93etbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ibm1vrbdc"/><path class="k_93etbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plunger-20-bold" {...props}></Icon>
