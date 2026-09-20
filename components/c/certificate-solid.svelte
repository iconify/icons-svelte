<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/iijut148h.css';
import '../../css/v/vgjh9ibgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="iijut148h"/><path class="vgjh9ibgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:certificate-solid" {...props}></Icon>
