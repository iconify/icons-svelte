<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/iecmi3svr.css';
import '../../css/n/n5amlrb_l.css';
import '../../css/v/vtz5mzbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="iecmi3svr"/><path class="n5amlrb_l"/><path class="vtz5mzbno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:focus-motion" {...props}></Icon>
