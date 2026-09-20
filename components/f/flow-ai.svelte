<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb89qzzmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zb89qzzmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:flow-ai" {...props}></Icon>
