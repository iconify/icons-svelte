<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nboi0qbgb.css';
import '../../css/z/zhh6u5bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nboi0qbgb"/><path class="zhh6u5bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:interconnector-20" {...props}></Icon>
