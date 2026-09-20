<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/epk0drb8m.css';
import '../../css/y/ynoqnxpwc.css';
import '../../css/i/i9g5gccvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="epk0drb8m"/><path class="ynoqnxpwc"/><path class="i9g5gccvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cables-usb-type-c" {...props}></Icon>
