<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uneym8l7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uneym8l7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-sound-in" {...props}></Icon>
