<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/z/zfrz8cbml.css';
import '../../css/i/imcwoeboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="zfrz8cbml"/><path class="imcwoeboq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:pen-2" {...props}></Icon>
