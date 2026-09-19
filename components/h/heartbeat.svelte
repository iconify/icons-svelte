<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we6_thbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="we6_thbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:heartbeat" {...props}></Icon>
