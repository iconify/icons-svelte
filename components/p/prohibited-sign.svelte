<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crsw-fb_d.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/y/y9f5wvx3z.css';
import '../../css/k/ksr_5bbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="crsw-fb_d"/><g class="jn8qy4bru"><path class="y9f5wvx3z"/><path class="ksr_5bbwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:prohibited-sign" {...props}></Icon>
