<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_spqu3na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_spqu3na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:minus-round" {...props}></Icon>
