<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7dfh_bxr.css';
import '../../css/d/doa6wmbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7dfh_bxr"/><path class="doa6wmbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prusa-connect" {...props}></Icon>
