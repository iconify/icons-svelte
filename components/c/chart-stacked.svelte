<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l1lh69b9o.css';
import '../../css/j/jzanc6bsn.css';
import '../../css/b/bw2p-ubhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l1lh69b9o"/><path class="jzanc6bsn"/><path class="bw2p-ubhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-stacked" {...props}></Icon>
