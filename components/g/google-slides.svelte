<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlxzqobyy.css';
import '../../css/y/y5z6dwezu.css';
import '../../css/a/akcxopd1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zlxzqobyy"/><path class="y5z6dwezu"/><path class="akcxopd1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-slides" {...props}></Icon>
