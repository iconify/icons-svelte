<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns-ktm3kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns-ktm3kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bar-chart-alt-2" {...props}></Icon>
