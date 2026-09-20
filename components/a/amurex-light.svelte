<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4fpidhjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4fpidhjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amurex-light" {...props}></Icon>
