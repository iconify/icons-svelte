<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdd82pb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdd82pb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:laptop-x" {...props}></Icon>
