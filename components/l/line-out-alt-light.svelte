<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/p5smuv1fx.css';
import '../../css/i/il0pwlb6n.css';
import '../../css/z/zimgjfjhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect transform="rotate(90 9 15)" class="p5smuv1fx"/><path class="il0pwlb6n"/><path class="zimgjfjhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-out-alt-light" {...props}></Icon>
