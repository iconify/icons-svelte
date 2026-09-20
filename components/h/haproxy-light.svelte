<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-4y4dmgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-4y4dmgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haproxy-light" {...props}></Icon>
