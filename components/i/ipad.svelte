<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx6-ytqrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jx6-ytqrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:ipad" {...props}></Icon>
