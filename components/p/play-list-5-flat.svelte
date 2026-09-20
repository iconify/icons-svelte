<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/inkrjwb3i.css';
import '../../css/g/gniky1bbo.css';
import '../../css/b/bwzd4r7_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="inkrjwb3i"/><path class="gniky1bbo"/><path class="bwzd4r7_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:play-list-5-flat" {...props}></Icon>
