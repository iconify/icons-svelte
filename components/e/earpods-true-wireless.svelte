<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/erjvk0bmc.css';
import '../../css/k/k2e__fuki.css';
import '../../css/i/i9fx_71ve.css';
import '../../css/d/dorrxzhyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="erjvk0bmc"/><path class="k2e__fuki"/><path class="i9fx_71ve"/><path class="dorrxzhyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:earpods-true-wireless" {...props}></Icon>
