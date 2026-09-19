<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gdklhuebv.css';
import '../../css/o/ouwye0b8s.css';
import '../../css/f/f5w20rbat.css';
import '../../css/h/hrlhvxdnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gdklhuebv"/><path class="ouwye0b8s"/><path class="f5w20rbat"/><path class="hrlhvxdnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dollar-bill-outline" {...props}></Icon>
