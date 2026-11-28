<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzz7np1_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzz7np1_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cat-heart" {...props}></Icon>
