<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q7d54sbwc.css';
import '../../css/k/k8xwvxi_d.css';
import '../../css/t/tgiuk7b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q7d54sbwc"/><path class="k8xwvxi_d"/><path class="tgiuk7b5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:merge-pdf-flat" {...props}></Icon>
