<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqw4w29bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqw4w29bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:commodore" {...props}></Icon>
