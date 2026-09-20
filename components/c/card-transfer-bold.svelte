<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gafy37gmj.css';
import '../../css/s/sjlz8xm0b.css';
import '../../css/r/ri_ieprmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gafy37gmj"/><path clip-rule="evenodd" class="sjlz8xm0b"/><path clip-rule="evenodd" class="ri_ieprmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-transfer-bold" {...props}></Icon>
