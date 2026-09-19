<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q39pzgo6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q39pzgo6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hospital" {...props}></Icon>
