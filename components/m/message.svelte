<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_n--ccjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t_n--ccjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:message" {...props}></Icon>
