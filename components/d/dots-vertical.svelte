<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fwa9t1wyp.css';
import '../../css/s/skr69mb3d.css';
import '../../css/k/k5jnlg1dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><rect class="fwa9t1wyp"/><rect class="skr69mb3d"/><rect class="k5jnlg1dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:dots-vertical" {...props}></Icon>
