<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsx3oj1sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nsx3oj1sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:firebase-solid" {...props}></Icon>
