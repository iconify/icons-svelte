<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9lgcu2_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9lgcu2_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-2-fill" {...props}></Icon>
