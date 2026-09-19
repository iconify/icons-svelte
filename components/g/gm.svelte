<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/okn4h4bva.css';
import '../../css/s/sgh8jz96b.css';
import '../../css/y/ycrtwzb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="okn4h4bva"/><path clip-rule="evenodd" class="sgh8jz96b"/><path class="ycrtwzb4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:gm" {...props}></Icon>
