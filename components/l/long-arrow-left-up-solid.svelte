<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqa3tkb1n.css';
import '../../css/t/t77t6gbxy.css';
import '../../css/g/ga300c6qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="t77t6gbxy"/><path class="ga300c6qn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:long-arrow-left-up-solid" {...props}></Icon>
