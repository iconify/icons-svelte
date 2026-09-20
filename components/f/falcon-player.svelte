<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g225s7bhh.css';
import '../../css/l/lqs3it20u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g225s7bhh"/><path class="lqs3it20u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:falcon-player" {...props}></Icon>
