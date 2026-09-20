<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1hu1o07m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1hu1o07m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-star-four-points" {...props}></Icon>
