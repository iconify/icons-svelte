<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpt1a073y.css';
import '../../css/z/zbfwn0b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kpt1a073y"/><path class="zbfwn0b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:psitransfer" {...props}></Icon>
