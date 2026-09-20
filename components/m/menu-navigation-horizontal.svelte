<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w8ab97v2n.css';
import '../../css/k/kcvvg0a8o.css';
import '../../css/k/kkgxl-zeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w8ab97v2n"/><path class="kcvvg0a8o"/><path class="kkgxl-zeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:menu-navigation-horizontal" {...props}></Icon>
