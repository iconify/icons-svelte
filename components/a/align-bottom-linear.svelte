<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jpo7_pb2a.css';
import '../../css/o/oy1zyc70h.css';
import '../../css/s/sflfg-b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jpo7_pb2a"/><path class="oy1zyc70h"/><path class="sflfg-b2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-bottom-linear" {...props}></Icon>
