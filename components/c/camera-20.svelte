<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbqaakbsr.css';
import '../../css/f/fys_hacng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fbqaakbsr"/><path class="fys_hacng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-20" {...props}></Icon>
