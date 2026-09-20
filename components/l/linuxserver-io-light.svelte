<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r66o14bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r66o14bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linuxserver-io-light" {...props}></Icon>
