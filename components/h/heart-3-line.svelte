<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q19o077cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q19o077cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-3-line" {...props}></Icon>
