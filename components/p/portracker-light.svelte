<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u89m-dgoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u89m-dgoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portracker-light" {...props}></Icon>
