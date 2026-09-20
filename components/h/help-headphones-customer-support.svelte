<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/khi4xmbpe.css';
import '../../css/d/dfxun4bwh.css';
import '../../css/o/oaveh2bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="khi4xmbpe"/><path class="dfxun4bwh"/><path class="oaveh2bmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:help-headphones-customer-support" {...props}></Icon>
