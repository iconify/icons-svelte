<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceag4wngd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceag4wngd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:foggy-fill" {...props}></Icon>
