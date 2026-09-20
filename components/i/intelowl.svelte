<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyc3qpksd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hyc3qpksd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intelowl" {...props}></Icon>
