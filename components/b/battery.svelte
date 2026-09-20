<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nbxszfrsi.css';
import '../../css/c/c2s7492ws.css';
import '../../css/k/kxw7_zabv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="nbxszfrsi"/><rect class="c2s7492ws"/><path class="kxw7_zabv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:battery" {...props}></Icon>
