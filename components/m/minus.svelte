<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7m--mxjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7m--mxjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:minus" {...props}></Icon>
