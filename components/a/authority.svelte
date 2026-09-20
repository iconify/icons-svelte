<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhe70kwmw.css';
import '../../css/f/f-6nxexvx.css';
import '../../css/w/wwemd7z7m.css';
import '../../css/w/wa4t1cfmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="bhe70kwmw"/><path class="f-6nxexvx"/><path class="wwemd7z7m"/><path class="wa4t1cfmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:authority" {...props}></Icon>
