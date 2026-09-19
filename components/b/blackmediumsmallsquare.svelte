<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0u060rxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v0u060rxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackmediumsmallsquare" {...props}></Icon>
