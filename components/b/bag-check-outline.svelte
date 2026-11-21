<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zydcpabso.css';
import '../../css/t/tbqohkbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zydcpabso"/><path class="tbqohkbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-check-outline" {...props}></Icon>
