<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/prxbgwngf.css';
import '../../css/u/ui-bcv6yx.css';
import '../../css/u/ubnma2bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="prxbgwngf"/><path class="ui-bcv6yx"/><path class="ubnma2bri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chef-hat-heart-duotone" {...props}></Icon>
