<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzonc9brq.css';
import '../../css/h/h2ks3p8yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzonc9brq"/><path class="h2ks3p8yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:monitor" {...props}></Icon>
