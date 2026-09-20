<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hinf7eusg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hinf7eusg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnify-add-cursor" {...props}></Icon>
