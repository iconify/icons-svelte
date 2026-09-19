<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erwi4obyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="erwi4obyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:growth-chart-fill-12" {...props}></Icon>
