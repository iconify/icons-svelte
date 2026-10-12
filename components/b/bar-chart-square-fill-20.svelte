<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo70snbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mo70snbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-square-fill-20" {...props}></Icon>
