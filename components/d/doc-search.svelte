<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gwzldfrvf.css';
import '../../css/m/mx362vb_b.css';
import '../../css/s/s3a1y7bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="gwzldfrvf"/><path class="mx362vb_b"/><path class="s3a1y7bdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:doc-search" {...props}></Icon>
