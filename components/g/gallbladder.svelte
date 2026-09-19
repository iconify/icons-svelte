<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptwtnnbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ptwtnnbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gallbladder" {...props}></Icon>
