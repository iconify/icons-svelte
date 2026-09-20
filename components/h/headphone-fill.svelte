<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix7mdhbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix7mdhbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:headphone-fill" {...props}></Icon>
