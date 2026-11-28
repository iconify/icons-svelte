<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t61-95bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t61-95bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:milk-check" {...props}></Icon>
