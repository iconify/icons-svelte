<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4-rnsbij.css';
import '../../css/m/mf2yaebts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4-rnsbij"/><path class="mf2yaebts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:baseball-sharp" {...props}></Icon>
