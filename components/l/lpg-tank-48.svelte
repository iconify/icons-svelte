<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5bjig3qg.css';
import '../../css/w/w9ts85b5q.css';
import '../../css/o/of5hjbcyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c5bjig3qg"/><path class="w9ts85b5q"/><path class="of5hjbcyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lpg-tank-48" {...props}></Icon>
