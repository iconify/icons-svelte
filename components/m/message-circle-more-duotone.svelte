<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cr23qknpj.css';
import '../../css/o/owcrvxbsm.css';
import '../../css/c/c17w8ny-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cr23qknpj"/><path class="owcrvxbsm"/><path class="c17w8ny-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-more-duotone" {...props}></Icon>
