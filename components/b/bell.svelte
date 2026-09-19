<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcf0a2x-v.css';
import '../../css/y/yr6qxeb0g.css';
import '../../css/l/lrjsqqbbm.css';
import '../../css/c/cd3dpacbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fcf0a2x-v"/><path class="yr6qxeb0g"/><path class="lrjsqqbbm"/><path class="cd3dpacbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bell" {...props}></Icon>
