<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v326h-n7o.css';
import '../../css/r/rc04i3pkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v326h-n7o"/><path class="rc04i3pkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planarally" {...props}></Icon>
