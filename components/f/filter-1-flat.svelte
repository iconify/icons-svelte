<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhoebh7hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zhoebh7hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:filter-1-flat" {...props}></Icon>
