<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh40-cbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zh40-cbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:click-to-fold" {...props}></Icon>
