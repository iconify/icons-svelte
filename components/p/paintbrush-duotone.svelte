<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/re31xacew.css';
import '../../css/x/xaqffbcng.css';
import '../../css/y/y6pqfebos.css';
import '../../css/n/n2wq2ypgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="re31xacew"/><path class="xaqffbcng"/><path class="y6pqfebos"/><path class="n2wq2ypgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paintbrush-duotone" {...props}></Icon>
