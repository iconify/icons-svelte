<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndtr3ub9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndtr3ub9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bookmark-off" {...props}></Icon>
