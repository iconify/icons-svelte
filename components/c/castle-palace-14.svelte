<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g469fvbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g469fvbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:castle-palace-14" {...props}></Icon>
