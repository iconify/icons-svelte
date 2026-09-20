<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aml4e2bhz.css';
import '../../css/o/oge-yxbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="aml4e2bhz"/><path class="oge-yxbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-imaging-root-category" {...props}></Icon>
