<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhkum03mr.css';
import '../../css/k/k_bic86zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hhkum03mr"/><path class="k_bic86zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gloves-20-bold" {...props}></Icon>
