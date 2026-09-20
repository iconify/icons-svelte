<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp_nt6zvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp_nt6zvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:heart-cupid" {...props}></Icon>
