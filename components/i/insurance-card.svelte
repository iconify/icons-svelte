<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh7vsxbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xh7vsxbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:insurance-card" {...props}></Icon>
