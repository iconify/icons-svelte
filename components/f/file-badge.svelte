<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bybr2q82h.css';
import '../../css/t/t34te5bfi.css';
import '../../css/g/gw45uub7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bybr2q82h"/><path class="t34te5bfi"/><path class="gw45uub7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-badge" {...props}></Icon>
