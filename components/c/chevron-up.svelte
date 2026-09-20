<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgskst78s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fgskst78s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chevron-up" {...props}></Icon>
