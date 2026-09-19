<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arxjvacib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="arxjvacib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nav-icon-a" {...props}></Icon>
