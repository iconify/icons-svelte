<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn_hwrb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qn_hwrb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:drone2x-outline" {...props}></Icon>
