<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs7c-ub3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zs7c-ub3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:crop" {...props}></Icon>
