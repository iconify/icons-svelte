<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l40jc9brz.css';
import '../../css/k/knv_kx8ky.css';
import '../../css/b/bek5jfb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l40jc9brz"/><path class="knv_kx8ky"/><path class="bek5jfb-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:golang" {...props}></Icon>
