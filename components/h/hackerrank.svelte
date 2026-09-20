<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj8x8hb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj8x8hb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hackerrank" {...props}></Icon>
