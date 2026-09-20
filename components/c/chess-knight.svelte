<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/b/bsfg6lbji.css';
import '../../css/a/au9rkbbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="bsfg6lbji"/><path class="au9rkbbkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:chess-knight" {...props}></Icon>
