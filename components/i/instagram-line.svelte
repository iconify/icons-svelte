<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izqo2de1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izqo2de1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:instagram-line" {...props}></Icon>
