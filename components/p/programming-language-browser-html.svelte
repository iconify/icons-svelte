<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j-wm-8r3v.css';
import '../../css/b/b34n1w8cn.css';
import '../../css/s/sslwlcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j-wm-8r3v"/><path class="b34n1w8cn"/><path class="sslwlcb4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:programming-language-browser-html" {...props}></Icon>
