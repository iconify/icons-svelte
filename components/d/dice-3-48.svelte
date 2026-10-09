<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr7h2fb6d.css';
import '../../css/z/zh73d2b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lr7h2fb6d"/><path class="zh73d2b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-3-48" {...props}></Icon>
