<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi86u_ule.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zi86u_ule"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firefly-iii-dark" {...props}></Icon>
