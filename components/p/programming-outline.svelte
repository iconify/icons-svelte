<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eyh5gf8py.css';
import '../../css/k/ke227gbwo.css';
import '../../css/k/k9825nbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eyh5gf8py"/><path class="ke227gbwo"/><path clip-rule="evenodd" class="k9825nbyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:programming-outline" {...props}></Icon>
