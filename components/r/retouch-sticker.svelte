<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dya8ib-fm.css';
import '../../css/g/gu0vjlbyc.css';
import '../../css/f/fja6vyb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dya8ib-fm"/><path class="gu0vjlbyc"/><path class="fja6vyb6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:retouch-sticker" {...props}></Icon>
