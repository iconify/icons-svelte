<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u_ec1fbcy.css';
import '../../css/c/cr23qknpj.css';
import '../../css/o/owcrvxbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u_ec1fbcy"/><path class="cr23qknpj"/><path class="owcrvxbsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-code-duotone" {...props}></Icon>
