<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic-zq4-uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ic-zq4-uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grok-light" {...props}></Icon>
