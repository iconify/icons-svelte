<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w81f2y0yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w81f2y0yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nuxt-light" {...props}></Icon>
