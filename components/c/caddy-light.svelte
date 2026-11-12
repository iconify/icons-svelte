<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cybvs067u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cybvs067u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caddy-light" {...props}></Icon>
