<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sbtg6tbae.css';
import '../../css/l/luizb6blp.css';
import '../../css/q/qo5oo6bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sbtg6tbae"/><path class="luizb6blp"/><path class="qo5oo6bzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lectern-duotone" {...props}></Icon>
