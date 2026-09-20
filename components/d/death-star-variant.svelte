<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z99gqz0zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z99gqz0zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:death-star-variant" {...props}></Icon>
