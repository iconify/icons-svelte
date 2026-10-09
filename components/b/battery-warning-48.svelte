<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5sfwb0q.css';
import '../../css/s/s_-b-lbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5sfwb0q"/><path class="s_-b-lbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-warning-48" {...props}></Icon>
