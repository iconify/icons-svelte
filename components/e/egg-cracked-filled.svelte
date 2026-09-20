<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udsm0l3hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udsm0l3hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:egg-cracked-filled" {...props}></Icon>
