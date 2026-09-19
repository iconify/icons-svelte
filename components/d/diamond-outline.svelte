<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vq6byr4cz.css';
import '../../css/r/rqobv64_l.css';
import '../../css/v/vbfg78blf.css';
import '../../css/o/ovpd07bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vq6byr4cz"/><path class="rqobv64_l"/><path class="vbfg78blf"/><path class="ovpd07bcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:diamond-outline" {...props}></Icon>
