<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mr7zqwbog.css';
import '../../css/u/usal8xb7u.css';
import '../../css/p/ph9bfgb1s.css';
import '../../css/v/vde5abbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mr7zqwbog"/><path class="usal8xb7u"/><path class="ph9bfgb1s"/><path class="vde5abbxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:network-connection-locked" {...props}></Icon>
