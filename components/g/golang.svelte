<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmgdm_xko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmgdm_xko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:golang" {...props}></Icon>
