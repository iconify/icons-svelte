<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv66cgbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qv66cgbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:job-status-level2x-outline" {...props}></Icon>
