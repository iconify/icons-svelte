<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca2293b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ca2293b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:dashboard-1-flat" {...props}></Icon>
