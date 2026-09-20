<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl88w1bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl88w1bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-social-light" {...props}></Icon>
