<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nxvyzpbvr.css';
import '../../css/s/sl2zlhbqn.css';
import '../../css/o/oc6808bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nxvyzpbvr"/><path class="sl2zlhbqn"/><path class="oc6808bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:color-picker" {...props}></Icon>
