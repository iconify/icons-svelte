<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha51odben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ha51odben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:patreon-light" {...props}></Icon>
