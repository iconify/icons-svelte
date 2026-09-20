<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2csbibpu.css';
import '../../css/m/mkb8spb3x.css';
import '../../css/w/wyoo44k5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":187.485};
const content = `<g class="g2csbibpu"><path class="mkb8spb3x"/><path class="wyoo44k5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bethesda" {...props}></Icon>
