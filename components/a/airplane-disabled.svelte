<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1jhl0l9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1jhl0l9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:airplane-disabled" {...props}></Icon>
