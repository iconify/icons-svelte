<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i-atxg24s.css';
import '../../css/n/nwt48v2tu.css';
import '../../css/u/u0_h6rcii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i-atxg24s"/><path class="nwt48v2tu"/><path class="u0_h6rcii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:database-filled" {...props}></Icon>
