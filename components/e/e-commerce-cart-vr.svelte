<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zxh1gybxr.css';
import '../../css/m/mr6yvobwm.css';
import '../../css/c/cmoblzk2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zxh1gybxr"/><path class="mr6yvobwm"/><path class="cmoblzk2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:e-commerce-cart-vr" {...props}></Icon>
