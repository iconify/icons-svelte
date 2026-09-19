<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na7q4z2mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="na7q4z2mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:history-stroke-12" {...props}></Icon>
