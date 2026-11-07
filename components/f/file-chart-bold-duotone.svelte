<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/a/a6rl69b5y.css';
import '../../css/b/br9a0t2td.css';
import '../../css/u/uy28rnb-n.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path class="a6rl69b5y"/><path class="br9a0t2td"/><path class="uy28rnb-n"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-chart-bold-duotone" {...props}></Icon>
