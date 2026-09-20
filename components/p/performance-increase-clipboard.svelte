<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n4v2kwb_q.css';
import '../../css/i/izo4pibwp.css';
import '../../css/a/au9wb8bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n4v2kwb_q"/><path class="izo4pibwp"/><path class="au9wb8bvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:performance-increase-clipboard" {...props}></Icon>
