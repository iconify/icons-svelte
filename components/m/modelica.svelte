<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtgl5k4ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mtgl5k4ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:modelica" {...props}></Icon>
