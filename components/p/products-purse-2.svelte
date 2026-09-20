<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kp6p4nvcu.css';
import '../../css/f/fhg14db3y.css';
import '../../css/q/qk-6jdbzy.css';
import '../../css/s/s1nku5boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kp6p4nvcu"/><path class="fhg14db3y"/><path class="qk-6jdbzy"/><path class="s1nku5boo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:products-purse-2" {...props}></Icon>
