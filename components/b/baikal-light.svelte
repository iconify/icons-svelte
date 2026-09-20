<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf63vxpfw.css';
import '../../css/h/hngcoxbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pf63vxpfw"/><path class="hngcoxbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baikal-light" {...props}></Icon>
