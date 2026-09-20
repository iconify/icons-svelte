<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhd5tfbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fhd5tfbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:light-snow-filled" {...props}></Icon>
