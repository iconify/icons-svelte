<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oe5p9oluz.css';
import '../../css/k/kl_0gnbjt.css';
import '../../css/o/omvblxb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oe5p9oluz"/><path class="kl_0gnbjt"/><path class="omvblxb5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:memory-sd-card" {...props}></Icon>
