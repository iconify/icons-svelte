<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4x8skmmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4x8skmmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coneshare-dark" {...props}></Icon>
