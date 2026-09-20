<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiyy8_k4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiyy8_k4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pihole" {...props}></Icon>
