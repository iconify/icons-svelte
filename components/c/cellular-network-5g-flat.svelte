<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n86dzd-gr.css';
import '../../css/h/h_rva6brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n86dzd-gr"/><path class="h_rva6brc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:cellular-network-5g-flat" {...props}></Icon>
