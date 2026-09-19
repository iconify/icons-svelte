<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m90omkbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m90omkbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lambda" {...props}></Icon>
