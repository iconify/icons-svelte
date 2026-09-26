<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sgmemqb3w.css';
import '../../css/f/fcfj16wrs.css';
import '../../css/t/tlmpzabnd.css';
import '../../css/s/sioybk19c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sgmemqb3w"/><path class="fcfj16wrs"/><path class="tlmpzabnd"/><path class="sioybk19c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:globe-bold" {...props}></Icon>
