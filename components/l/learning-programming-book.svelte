<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n1yi6yvsv.css';
import '../../css/u/uqov-ibdi.css';
import '../../css/x/xx3inh7rz.css';
import '../../css/g/ggoszyzqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n1yi6yvsv"/><path class="uqov-ibdi"/><path class="xx3inh7rz"/><path class="ggoszyzqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:learning-programming-book" {...props}></Icon>
