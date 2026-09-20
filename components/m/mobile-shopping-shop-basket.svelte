<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qyls5gb_b.css';
import '../../css/x/xej79-bhm.css';
import '../../css/f/fju8uwbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qyls5gb_b"/><path class="xej79-bhm"/><path class="fju8uwbfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:mobile-shopping-shop-basket" {...props}></Icon>
