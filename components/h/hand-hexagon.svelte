<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/t/twlvgibdw.css';
import '../../css/e/eyclxt8ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="twlvgibdw"/><path class="eyclxt8ne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:hand-hexagon" {...props}></Icon>
