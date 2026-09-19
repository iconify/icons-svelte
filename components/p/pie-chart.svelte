<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no1dsegho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="no1dsegho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:pie-chart" {...props}></Icon>
