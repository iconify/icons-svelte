<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y3fqx3qzw.css';
import '../../css/n/n1d6mcb2n.css';
import '../../css/e/ew9obfnmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y3fqx3qzw"/><path class="n1d6mcb2n"/><path clip-rule="evenodd" class="ew9obfnmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medical-kit-bold-duotone" {...props}></Icon>
