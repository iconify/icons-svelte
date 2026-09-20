<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi4f-hakj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi4f-hakj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-frown" {...props}></Icon>
