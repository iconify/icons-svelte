<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/ntqqlf_wk.css';
import '../../css/m/m0bhoobwp.css';
import '../../css/l/lejiw1pae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ntqqlf_wk"/><path class="m0bhoobwp"/><path class="lejiw1pae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:arrow-down-left" {...props}></Icon>
