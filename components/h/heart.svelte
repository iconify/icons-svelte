<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmgzq2rae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fmgzq2rae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:heart" {...props}></Icon>
