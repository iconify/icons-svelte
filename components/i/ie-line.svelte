<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd3epf6yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3epf6yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ie-line" {...props}></Icon>
