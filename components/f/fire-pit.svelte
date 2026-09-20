<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9oyy4bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g9oyy4bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fire-pit" {...props}></Icon>
