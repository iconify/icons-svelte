<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hghk2kapn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hghk2kapn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsblur-light" {...props}></Icon>
