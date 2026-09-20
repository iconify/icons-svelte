<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_raf5bng.css';
import '../../css/k/k9xu8tbyg.css';
import '../../css/j/jcs05xofn.css';
import '../../css/l/la3iaobmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="e_raf5bng"><path class="k9xu8tbyg"/><path class="jcs05xofn"/></g><path class="la3iaobmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heart-hands-dark-skin-tone" {...props}></Icon>
