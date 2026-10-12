<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cr23qknpj.css';
import '../../css/o/owcrvxbsm.css';
import '../../css/m/mlgs6bbau.css';
import '../../css/n/nbws00oqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cr23qknpj"/><path class="owcrvxbsm"/><path class="mlgs6bbau"/><path class="nbws00oqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-reply-duotone" {...props}></Icon>
