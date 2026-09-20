<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_4s31bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_4s31bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kick-scooter-broken" {...props}></Icon>
