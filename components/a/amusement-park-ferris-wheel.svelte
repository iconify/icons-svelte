<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/owjk9o9eq.css';
import '../../css/a/a-hn66c-d.css';
import '../../css/x/xohw_uboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="owjk9o9eq"/><path class="a-hn66c-d"/><path class="xohw_uboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:amusement-park-ferris-wheel" {...props}></Icon>
