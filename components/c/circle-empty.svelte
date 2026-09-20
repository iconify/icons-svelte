<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzd0j5pdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qzd0j5pdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:circle-empty" {...props}></Icon>
