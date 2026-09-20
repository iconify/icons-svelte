<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow0e6s8yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow0e6s8yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:passbolt-dark" {...props}></Icon>
