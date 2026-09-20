<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxwc_6_yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxwc_6_yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privatebin-light" {...props}></Icon>
