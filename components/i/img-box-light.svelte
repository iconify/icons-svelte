<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vfkom2b1l.css';
import '../../css/l/lja5wgb3w.css';
import '../../css/k/k0evexoqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vfkom2b1l"/><path clip-rule="evenodd" class="lja5wgb3w"/><circle class="k0evexoqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:img-box-light" {...props}></Icon>
