<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ern78-ehy.css';
import '../../css/f/fw0wa3b7e.css';
import '../../css/l/lbze0hblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ern78-ehy"/><path class="fw0wa3b7e"/><path class="lbze0hblg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:ai-folder-robot-flat" {...props}></Icon>
