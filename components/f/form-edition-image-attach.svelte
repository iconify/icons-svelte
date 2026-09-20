<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q_sgc5ccm.css';
import '../../css/t/tnt2-yler.css';
import '../../css/r/rpvb5zbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q_sgc5ccm"/><path class="tnt2-yler"/><path class="rpvb5zbto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:form-edition-image-attach" {...props}></Icon>
