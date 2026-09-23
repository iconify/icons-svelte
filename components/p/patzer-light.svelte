<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmoj0pv_m.css';
import '../../css/i/iuvjulbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmoj0pv_m"/><path class="iuvjulbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:patzer-light" {...props}></Icon>
