<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz9i9u2gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uz9i9u2gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openvas-light" {...props}></Icon>
