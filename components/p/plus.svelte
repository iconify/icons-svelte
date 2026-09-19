<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/u/uqz3ssidv.css';
import '../../css/g/gab0h-cqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="uqz3ssidv"/><path class="gab0h-cqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:plus" {...props}></Icon>
