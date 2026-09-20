<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxlm-sbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="oxlm-sbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:alpine-hut-14" {...props}></Icon>
