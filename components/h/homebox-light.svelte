<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxrlaebjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxrlaebjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homebox-light" {...props}></Icon>
