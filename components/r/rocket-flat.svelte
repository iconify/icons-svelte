<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/amyp15iwt.css';
import '../../css/d/d7g16bb0d.css';
import '../../css/a/ad36n-bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="amyp15iwt"/><path class="d7g16bb0d"/><path class="ad36n-bbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:rocket-flat" {...props}></Icon>
