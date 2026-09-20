<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs8s6vbov.css';
import '../../css/a/a6q-egbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13547,"height":4513};
const content = `<path class="bs8s6vbov"/><path class="a6q-egbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bybit" {...props}></Icon>
