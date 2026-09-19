<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy8lnwbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy8lnwbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:building-03" {...props}></Icon>
