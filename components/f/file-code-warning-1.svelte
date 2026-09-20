<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pwpjv5bhc.css';
import '../../css/s/sx98n481k.css';
import '../../css/e/e2qt_5bqy.css';
import '../../css/x/xq45cg75b.css';
import '../../css/p/py5tbrbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pwpjv5bhc"/><path class="sx98n481k"/><path class="e2qt_5bqy"/><path class="xq45cg75b"/><path class="py5tbrbev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:file-code-warning-1" {...props}></Icon>
