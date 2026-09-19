<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xr5qhnbxd.css';
import '../../css/w/wwb7e_b9q.css';
import '../../css/g/g4oh7sjkc.css';
import '../../css/o/ohjhefb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xr5qhnbxd"/><path class="wwb7e_b9q"/><path class="g4oh7sjkc"/><path class="ohjhefb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:pencil-paintbrush" {...props}></Icon>
