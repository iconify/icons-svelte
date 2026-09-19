<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzdetfb7j.css';
import '../../css/w/w8qy4b3yq.css';
import '../../css/r/r83kv-bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzdetfb7j"/><path class="w8qy4b3yq"/><path class="r83kv-bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pagewithcurl" {...props}></Icon>
