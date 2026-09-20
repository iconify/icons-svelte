<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwa2j_kng.css';
import '../../css/c/cwd0g7-xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="pwa2j_kng"/><path class="cwd0g7-xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:large-intestine" {...props}></Icon>
