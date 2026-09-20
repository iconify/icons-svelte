<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssa8p6a4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ssa8p6a4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:building-door" {...props}></Icon>
