<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e4nz8hbbh.css';
import '../../css/v/vpbpywzov.css';
import '../../css/w/wzw9_ibbf.css';
import '../../css/v/vesenmbfb.css';
import '../../css/a/a7_0t4bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e4nz8hbbh"/><path class="vpbpywzov"/><path class="wzw9_ibbf"/><path class="vesenmbfb"/><path class="a7_0t4bbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:modern-music-drums" {...props}></Icon>
