<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5oob6yvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5oob6yvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-search" {...props}></Icon>
