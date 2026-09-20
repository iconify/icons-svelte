<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l41g2w51k.css';
import '../../css/w/w98s6ebmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="l41g2w51k"/><path class="w98s6ebmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cross-country-skiing" {...props}></Icon>
