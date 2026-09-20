<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l-5lbndex.css';
import '../../css/o/oe2fmx3ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="ft5dv1b6b"><path class="l-5lbndex"/><path class="oe2fmx3ou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:cloud-duotone" {...props}></Icon>
