<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/ptjn9dspd.css';
import '../../css/s/snfwzgyfx.css';
import '../../css/l/lh9k_h7vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ptjn9dspd"/><path clip-rule="evenodd" class="snfwzgyfx"/><path class="lh9k_h7vv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:alarm-clock" {...props}></Icon>
