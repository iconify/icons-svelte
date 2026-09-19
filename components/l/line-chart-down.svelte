<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn8wa8oth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn8wa8oth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:line-chart-down" {...props}></Icon>
