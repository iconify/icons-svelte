<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k1mzqdb1d.css';
import '../../css/x/xk748gddn.css';
import '../../css/y/yntq6xb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k1mzqdb1d"/><path class="xk748gddn"/><path clip-rule="evenodd" class="yntq6xb5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:file-zip" {...props}></Icon>
