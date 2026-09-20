<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zarvw4bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zarvw4bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-question" {...props}></Icon>
