<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxl4ujboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cxl4ujboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nerve-outline" {...props}></Icon>
