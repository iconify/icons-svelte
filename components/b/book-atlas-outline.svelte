<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xs-u7yzzn.css';
import '../../css/x/x-5hy_bas.css';
import '../../css/w/whpix6b2m.css';
import '../../css/n/n6dololes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xs-u7yzzn"/><path class="x-5hy_bas"/><path class="whpix6b2m"/><path class="n6dololes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-atlas-outline" {...props}></Icon>
