<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mnx9fobfp.css';
import '../../css/v/vmlbzhbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path class="mnx9fobfp"/><path class="vmlbzhbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:neo4j-wordmark" {...props}></Icon>
