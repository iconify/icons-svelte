<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah0ggz9pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ah0ggz9pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:piggy-bank" {...props}></Icon>
