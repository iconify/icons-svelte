<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/ws5ialpkt.css';
import '../../css/r/rsvkr-3pv.css';
import '../../css/q/qil03rubo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ws5ialpkt"/><path class="rsvkr-3pv"/><path class="qil03rubo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:email-action-reply-1" {...props}></Icon>
