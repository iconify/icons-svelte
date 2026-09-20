<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m_5mkzbsi.css';
import '../../css/r/r-81zlrts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m_5mkzbsi"/><path clip-rule="evenodd" class="r-81zlrts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:inbox-post-flat" {...props}></Icon>
