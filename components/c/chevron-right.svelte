<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dea9v34fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dea9v34fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevron-right" {...props}></Icon>
