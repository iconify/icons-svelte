<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh6v7rbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vh6v7rbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netlify-light" {...props}></Icon>
