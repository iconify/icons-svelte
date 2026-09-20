<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtph6ub4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mtph6ub4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-down-right" {...props}></Icon>
