<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l65irgbeq.css';
import '../../css/h/h-ks45b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l65irgbeq"/><path class="h-ks45b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:headplane-light" {...props}></Icon>
