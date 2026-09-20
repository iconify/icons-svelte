<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6q_tob7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6q_tob7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-spotify-filled" {...props}></Icon>
