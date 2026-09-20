<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an7_bbc4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an7_bbc4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reveal-js-dark" {...props}></Icon>
