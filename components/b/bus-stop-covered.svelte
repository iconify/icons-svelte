<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-zo8jdsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-zo8jdsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-stop-covered" {...props}></Icon>
