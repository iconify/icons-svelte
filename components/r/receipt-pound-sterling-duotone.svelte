<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yti9eh2tw.css';
import '../../css/c/c5mar1biz.css';
import '../../css/g/g48c9l9px.css';
import '../../css/f/f3at6bbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yti9eh2tw"/><path class="c5mar1biz"/><path class="g48c9l9px"/><path class="f3at6bbeu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-pound-sterling-duotone" {...props}></Icon>
