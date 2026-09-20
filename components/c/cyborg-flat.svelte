<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mo0jvlb2k.css';
import '../../css/z/zdil9-bok.css';
import '../../css/m/mhxwe-b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mo0jvlb2k"/><path class="zdil9-bok"/><path class="mhxwe-b9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cyborg-flat" {...props}></Icon>
