<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe2xp6bxc.css';
import '../../css/q/qa72txrwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pe2xp6bxc"/><path class="qa72txrwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fhem" {...props}></Icon>
