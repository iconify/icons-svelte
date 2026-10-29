<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j6807mbiw.css';
import '../../css/z/z4bbp2bhq.css';
import '../../css/q/q8vdfbk1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j6807mbiw"/><path class="wm-a z4bbp2bhq"/><path class="q8vdfbk1f wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-cog" {...props}></Icon>
