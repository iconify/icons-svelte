<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxnw_pr2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxnw_pr2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hammer-sharp" {...props}></Icon>
