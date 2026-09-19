<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy1re-qcg.css';
import '../../css/l/lodosdbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="qy1re-qcg"/><circle class="lodosdbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:decimal-stroke-16" {...props}></Icon>
