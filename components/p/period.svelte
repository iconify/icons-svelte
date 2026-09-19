<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhucej_2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zhucej_2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:period" {...props}></Icon>
