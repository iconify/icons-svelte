<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3arwzbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3arwzbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pie-chart-search" {...props}></Icon>
