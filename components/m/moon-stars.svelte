<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inf75xt8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inf75xt8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:moon-stars" {...props}></Icon>
