<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccemtwbeg.css';
import '../../css/w/w3qhuhbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ccemtwbeg"/><path class="w3qhuhbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:high-voltage" {...props}></Icon>
