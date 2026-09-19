<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w856n9bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1536};
const content = `<path class="w856n9bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bold" {...props}></Icon>
