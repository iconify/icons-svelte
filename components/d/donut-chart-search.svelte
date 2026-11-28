<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7jmjfvon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7jmjfvon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:donut-chart-search" {...props}></Icon>
