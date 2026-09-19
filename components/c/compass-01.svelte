<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sm58dfblq.css';
import '../../css/z/z2o0ujiuj.css';
import '../../css/q/qdv9qd58a.css';
import '../../css/d/d330q5myy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sm58dfblq"/><circle class="z2o0ujiuj"/><path class="qdv9qd58a"/><path class="d330q5myy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:compass-01" {...props}></Icon>
