<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuhqa_xqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fuhqa_xqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:letrina-outline" {...props}></Icon>
