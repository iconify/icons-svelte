<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zs8bi0bys.css';
import '../../css/s/sh3xxe9ap.css';
import '../../css/f/f4vx4ccga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zs8bi0bys"/><path class="sh3xxe9ap"/><path class="f4vx4ccga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:headphones-off-sharp-duotone" {...props}></Icon>
