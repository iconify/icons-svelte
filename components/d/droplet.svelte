<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgb63nblv.css';
import '../../css/b/btx5mjbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgb63nblv"/><path class="btx5mjbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:droplet" {...props}></Icon>
