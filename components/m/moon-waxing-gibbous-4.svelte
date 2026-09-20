<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsa_t_p5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="nsa_t_p5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waxing-gibbous-4" {...props}></Icon>
