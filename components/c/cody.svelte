<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lg3oiabbn.css';
import '../../css/l/l41a-6b0f.css';
import '../../css/m/mow9f5btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":55,"height":50};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lg3oiabbn"/><path class="l41a-6b0f"/><path class="mow9f5btu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cody" {...props}></Icon>
