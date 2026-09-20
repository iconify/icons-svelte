<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6torgwdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6torgwdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-g-box" {...props}></Icon>
