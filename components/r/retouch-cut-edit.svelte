<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xd424yelu.css';
import '../../css/d/d8xjnkbxa.css';
import '../../css/w/wwkxdntgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xd424yelu"/><path class="d8xjnkbxa"/><path class="wwkxdntgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:retouch-cut-edit" {...props}></Icon>
