<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xltvcrbmc.css';
import '../../css/w/wfvnn4b4v.css';
import '../../css/z/z19uyob6s.css';
import '../../css/o/om7eewmok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xltvcrbmc"/><path class="wfvnn4b4v"/><path class="z19uyob6s"/><path class="om7eewmok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cash-payment-bill" {...props}></Icon>
