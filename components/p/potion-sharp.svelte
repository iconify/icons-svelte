<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj0fax-7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj0fax-7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:potion-sharp" {...props}></Icon>
