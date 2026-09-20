<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf7pwmbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf7pwmbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloudflare-pages" {...props}></Icon>
