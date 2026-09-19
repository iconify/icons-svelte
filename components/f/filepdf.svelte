<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0cmx46aa.css';
import '../../css/b/btx7j3qro.css';
import '../../css/k/k8x4m_bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="x0cmx46aa"/><path class="btx7j3qro"/><path class="k8x4m_bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:filepdf" {...props}></Icon>
