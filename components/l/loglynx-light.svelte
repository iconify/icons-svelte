<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm91581ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wm91581ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:loglynx-light" {...props}></Icon>
