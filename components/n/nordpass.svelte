<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuf42lb8e.css';
import '../../css/m/m32r68bkv.css';
import '../../css/u/uinv5kb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="kuf42lb8e"><path class="m32r68bkv"/><path class="uinv5kb7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nordpass" {...props}></Icon>
