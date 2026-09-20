<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vti7h_4la.css';
import '../../css/z/znvm40bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-7};
const content = `<g class="cuyn6tgcc"><circle class="vti7h_4la"/><circle class="znvm40bms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flickr" {...props}></Icon>
