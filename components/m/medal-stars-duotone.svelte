<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ajfk-ob1k.css';
import '../../css/w/wpm_ts59c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ajfk-ob1k"/><path clip-rule="evenodd" class="wpm_ts59c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:medal-stars-duotone" {...props}></Icon>
