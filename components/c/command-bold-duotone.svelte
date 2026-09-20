<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k0512fcyc.css';
import '../../css/m/m1enbabxz.css';
import '../../css/o/ofz9dkbtj.css';
import '../../css/c/czi505bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0512fcyc"/><path class="m1enbabxz"/><path clip-rule="evenodd" class="ofz9dkbtj"/><path class="czi505bfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:command-bold-duotone" {...props}></Icon>
