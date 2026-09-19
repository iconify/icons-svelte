<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rywc8nbcc.css';
import '../../css/m/mh7spwbcm.css';
import '../../css/l/lzxnqd56o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rywc8nbcc"/><circle class="mh7spwbcm"/><circle class="lzxnqd56o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heavydivisionsign" {...props}></Icon>
