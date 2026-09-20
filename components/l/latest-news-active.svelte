<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu3bs6vzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu3bs6vzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:latest-news-active" {...props}></Icon>
