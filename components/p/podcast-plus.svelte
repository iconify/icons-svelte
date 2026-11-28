<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7re14t_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7re14t_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podcast-plus" {...props}></Icon>
