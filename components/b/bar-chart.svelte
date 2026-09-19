<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsj5r1bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="bsj5r1bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bar-chart" {...props}></Icon>
