<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpt1a073y.css';
import '../../css/h/hczeqh3lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kpt1a073y"/><path class="hczeqh3lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:psitransfer" {...props}></Icon>
