<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0t8p3g6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0t8p3g6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plug-check" {...props}></Icon>
