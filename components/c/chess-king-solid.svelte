<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogygfci6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogygfci6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chess-king-solid" {...props}></Icon>
