<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0eo731hg.css';
import '../../css/m/mwt8libml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0eo731hg"/><path class="mwt8libml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:alienmonster" {...props}></Icon>
