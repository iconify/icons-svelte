<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5792dbmu.css';
import '../../css/l/l80m0bc3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5792dbmu"/><path class="l80m0bc3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-brush" {...props}></Icon>
