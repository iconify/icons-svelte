<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsgjtvbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zsgjtvbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-4-level" {...props}></Icon>
