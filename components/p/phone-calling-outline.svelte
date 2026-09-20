<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zovzpjbnp.css';
import '../../css/z/zrk0uqbtm.css';
import '../../css/p/py4tdmbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zovzpjbnp"/><path class="zrk0uqbtm"/><path class="py4tdmbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-outline" {...props}></Icon>
