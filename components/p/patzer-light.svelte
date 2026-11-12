<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmoj0pv_m.css';
import '../../css/m/ml0m__bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmoj0pv_m"/><path class="ml0m__bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:patzer-light" {...props}></Icon>
