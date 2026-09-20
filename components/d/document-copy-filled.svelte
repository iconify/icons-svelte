<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qmijmpbpd.css';
import '../../css/g/gdpi26mpl.css';
import '../../css/v/vhe5-sisy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qmijmpbpd"/><path class="gdpi26mpl"/><path class="vhe5-sisy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document-copy-filled" {...props}></Icon>
