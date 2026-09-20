<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wgum6wtue.css';
import '../../css/d/d30dd2pkp.css';
import '../../css/g/g4-pf7_je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wgum6wtue"/><path class="d30dd2pkp"/><path class="g4-pf7_je"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cash-payment-bag-1" {...props}></Icon>
