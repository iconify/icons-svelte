<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7e1lvb-a.css';
import '../../css/i/i-u8wbcid.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/o5a5dzf_w.css';
import '../../css/p/p89qpiyno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="t7e1lvb-a"/><path class="i-u8wbcid"/><g class="jn8qy4bru"><path class="o5a5dzf_w"/><circle class="p89qpiyno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:female-sign" {...props}></Icon>
