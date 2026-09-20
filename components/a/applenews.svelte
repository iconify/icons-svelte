<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu3lde57s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu3lde57s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:applenews" {...props}></Icon>
