<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke4yrccol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ke4yrccol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fist-palm-salute" {...props}></Icon>
