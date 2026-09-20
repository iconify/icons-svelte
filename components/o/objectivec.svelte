<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkd72tfms.css';
import '../../css/q/qjl5pfj7i.css';
import '../../css/l/lkubu127s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="kkd72tfms"><path class="qjl5pfj7i"/><path class="lkubu127s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:objectivec" {...props}></Icon>
