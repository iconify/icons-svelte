<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_nhushwe.css';
import '../../css/d/dvyctl1bu.css';
import '../../css/w/wvf8eitqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z_nhushwe"/><path class="dvyctl1bu"/><path class="wvf8eitqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flight-roster" {...props}></Icon>
