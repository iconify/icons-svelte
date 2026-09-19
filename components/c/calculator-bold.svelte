<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvlvhpb4k.css';
import '../../css/c/craj1zw4d.css';
import '../../css/o/opzubsbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cvlvhpb4k"><path class="craj1zw4d"/><path class="opzubsbfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calculator-bold" {...props}></Icon>
