<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di3t_vcmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="di3t_vcmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-pie" {...props}></Icon>
