<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngs197bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ngs197bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:doctor2x-outline" {...props}></Icon>
