<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3luk2kpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="h3luk2kpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-showers" {...props}></Icon>
