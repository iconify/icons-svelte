<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raytajbvb.css';
import '../../css/s/sez2fgw8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="raytajbvb"/><path class="sez2fgw8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:book-open-bookmark-bold" {...props}></Icon>
