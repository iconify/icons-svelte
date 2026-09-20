<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zdl255bfm.css';
import '../../css/s/s-hbz213j.css';
import '../../css/a/a0jk60bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zdl255bfm"/><path class="s-hbz213j"/><path class="a0jk60bqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:camera" {...props}></Icon>
