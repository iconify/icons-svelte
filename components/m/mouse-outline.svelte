<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yv5nmtbub.css';
import '../../css/o/ou1ioiq0r.css';
import '../../css/v/vtzfhcinh.css';
import '../../css/h/hdbvy6x6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yv5nmtbub"/><path class="ou1ioiq0r"/><path class="vtzfhcinh"/><path class="hdbvy6x6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mouse-outline" {...props}></Icon>
