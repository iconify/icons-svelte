<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fssu8fvgl.css';
import '../../css/p/pplhre8-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fssu8fvgl"/><path class="pplhre8-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homelable-dark" {...props}></Icon>
