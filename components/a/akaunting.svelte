<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m17lhab3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m17lhab3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:akaunting" {...props}></Icon>
