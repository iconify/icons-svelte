<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l26-ium8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l26-ium8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:job-status-level" {...props}></Icon>
