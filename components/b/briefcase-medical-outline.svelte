<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o_-d6f-tc.css';
import '../../css/n/nx05ijkma.css';
import '../../css/h/hmbv5jbil.css';
import '../../css/x/xjsinqbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o_-d6f-tc"/><path class="nx05ijkma"/><path class="hmbv5jbil"/><path class="xjsinqbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:briefcase-medical-outline" {...props}></Icon>
