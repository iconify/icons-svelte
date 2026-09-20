<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_llbcob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bv_llbcob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:cath-lab" {...props}></Icon>
