<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f07qn6rfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f07qn6rfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:markdown" {...props}></Icon>
