<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y24yad2xd.css';
import '../../css/x/x-9xzubdm.css';
import '../../css/s/siob3cbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="y24yad2xd"/><path clip-rule="evenodd" class="x-9xzubdm"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dizzy2x-outline" {...props}></Icon>
