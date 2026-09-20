<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccjmkbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iccjmkbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nordvpn-light" {...props}></Icon>
