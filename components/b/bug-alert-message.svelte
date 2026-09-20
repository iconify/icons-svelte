<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q_w4odb-d.css';
import '../../css/s/sgz7esb3w.css';
import '../../css/a/ad1418b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q_w4odb-d"/><path class="sgz7esb3w"/><path class="ad1418b5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:bug-alert-message" {...props}></Icon>
