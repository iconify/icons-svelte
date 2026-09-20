<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z_vk08bfm.css';
import '../../css/j/jx05nhb6j.css';
import '../../css/m/m-i-p4irg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z_vk08bfm"/><path class="jx05nhb6j"/><path class="m-i-p4irg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:disability-partially-blind" {...props}></Icon>
