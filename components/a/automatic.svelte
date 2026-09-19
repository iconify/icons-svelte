<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6m34_-qc.css';
import '../../css/h/h-3i78bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6m34_-qc"/><path class="h-3i78bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:automatic" {...props}></Icon>
