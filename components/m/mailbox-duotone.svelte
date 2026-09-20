<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pansh_bqv.css';
import '../../css/k/k7wymaclk.css';
import '../../css/j/jwsgkxbib.css';
import '../../css/s/sitkwvw3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pansh_bqv"/><path class="k7wymaclk"/><path class="jwsgkxbib"/><path clip-rule="evenodd" class="sitkwvw3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mailbox-duotone" {...props}></Icon>
