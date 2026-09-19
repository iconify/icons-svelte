<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de1j8m3zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="de1j8m3zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:azure-wordmark" {...props}></Icon>
