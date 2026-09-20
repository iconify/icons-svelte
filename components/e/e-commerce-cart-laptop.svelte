<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oqg364tlq.css';
import '../../css/q/qq-clrhce.css';
import '../../css/r/r68pqmbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oqg364tlq"/><path class="qq-clrhce"/><path class="r68pqmbnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:e-commerce-cart-laptop" {...props}></Icon>
