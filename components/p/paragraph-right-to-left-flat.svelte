<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lurau-bqx.css';
import '../../css/p/pc3w89bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lurau-bqx"/><path class="pc3w89bje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:paragraph-right-to-left-flat" {...props}></Icon>
