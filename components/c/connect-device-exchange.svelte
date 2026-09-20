<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rj6-sg7sb.css';
import '../../css/a/asamhsb1h.css';
import '../../css/f/fk0hwpbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rj6-sg7sb"/><path class="asamhsb1h"/><path class="fk0hwpbxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:connect-device-exchange" {...props}></Icon>
