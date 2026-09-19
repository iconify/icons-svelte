<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfs41yb4d.css';
import '../../css/a/a9y45tbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfs41yb4d"/><path class="a9y45tbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bookmark-heart" {...props}></Icon>
