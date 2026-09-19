<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm0ys2uoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm0ys2uoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-down" {...props}></Icon>
