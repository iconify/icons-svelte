<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtqv6pbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vtqv6pbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:arm-outline" {...props}></Icon>
