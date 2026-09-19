<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg15pabpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hg15pabpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:axios-wordmark" {...props}></Icon>
