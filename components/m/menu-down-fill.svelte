<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbtm7uq1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pbtm7uq1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:menu-down-fill" {...props}></Icon>
