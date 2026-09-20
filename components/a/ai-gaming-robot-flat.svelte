<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c-afv9q-c.css';
import '../../css/x/x5fefv7uq.css';
import '../../css/g/g_aicbc-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="c-afv9q-c"/><path class="x5fefv7uq"/><path class="g_aicbc-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:ai-gaming-robot-flat" {...props}></Icon>
