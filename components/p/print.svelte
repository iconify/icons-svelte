<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv3-k1ocu.css';
import '../../css/h/hxk53pb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xv3-k1ocu"/><path class="hxk53pb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:print" {...props}></Icon>
