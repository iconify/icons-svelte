<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eczgn9bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eczgn9bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:bar-chart-2" {...props}></Icon>
