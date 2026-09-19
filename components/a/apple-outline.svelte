<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/droj9cnwk.css';
import '../../css/i/iydim6b0y.css';
import '../../css/a/a-u-nibzd.css';
import '../../css/m/mdfog5bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="droj9cnwk"/><path class="iydim6b0y"/><path class="a-u-nibzd"/><path class="mdfog5bdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:apple-outline" {...props}></Icon>
