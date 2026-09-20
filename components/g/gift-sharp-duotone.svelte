<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/h9jzwwozo.css';
import '../../css/l/lcfzjg4-r.css';
import '../../css/q/qhqq588lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h9jzwwozo"/><path class="lcfzjg4-r"/><path class="qhqq588lg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gift-sharp-duotone" {...props}></Icon>
