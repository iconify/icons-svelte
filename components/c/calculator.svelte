<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi18t8sbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="mi18t8sbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:calculator" {...props}></Icon>
