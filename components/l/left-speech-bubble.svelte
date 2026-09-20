<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djj-rrvqc.css';
import '../../css/w/w3-ezh4fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="djj-rrvqc"/><path class="w3-ezh4fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:left-speech-bubble" {...props}></Icon>
