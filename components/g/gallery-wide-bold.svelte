<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4t6-ibdt.css';
import '../../css/y/ywqmrebdw.css';
import '../../css/x/xxzrkjbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z4t6-ibdt"/><path clip-rule="evenodd" class="ywqmrebdw"/><path class="xxzrkjbgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-wide-bold" {...props}></Icon>
