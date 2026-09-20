<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yf85lrfdg.css';
import '../../css/o/othbtsbmg.css';
import '../../css/y/ywoivubqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yf85lrfdg"/><path class="othbtsbmg"/><path class="ywoivubqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:office-stamp-document" {...props}></Icon>
