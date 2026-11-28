<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9zc6b42h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9zc6b42h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-arrow-right" {...props}></Icon>
