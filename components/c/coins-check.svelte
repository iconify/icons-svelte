<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa-81x8rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa-81x8rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coins-check" {...props}></Icon>
