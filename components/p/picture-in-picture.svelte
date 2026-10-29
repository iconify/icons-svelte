<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9nmfjvdw.css';
import '../../css/r/r9swm8bzp.css';
import '../../css/y/y4nfpvt4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9nmfjvdw wm-k"/><path class="r9swm8bzp wm-k"/><path class="wm-a y4nfpvt4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:picture-in-picture" {...props}></Icon>
