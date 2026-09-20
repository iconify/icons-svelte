<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rha4cub7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rha4cub7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ford" {...props}></Icon>
