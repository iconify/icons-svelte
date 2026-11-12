<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrcqh2b6o.css';
import '../../css/x/xw_9y5bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hrcqh2b6o"/><path class="xw_9y5bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pomerium-light" {...props}></Icon>
