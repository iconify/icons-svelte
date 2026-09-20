<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/noo63lbvs.css';
import '../../css/g/gldq60b_b.css';
import '../../css/w/wdxiyjbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="noo63lbvs"/><path class="gldq60b_b"/><path class="wdxiyjbdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:color-picker-drop" {...props}></Icon>
