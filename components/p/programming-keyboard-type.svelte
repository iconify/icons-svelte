<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pu33yvb-i.css';
import '../../css/g/g-oo9qbrr.css';
import '../../css/h/h9a9_1b9v.css';
import '../../css/y/ye-ibsbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pu33yvb-i"/><path class="g-oo9qbrr"/><path class="h9a9_1b9v"/><path class="ye-ibsbpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:programming-keyboard-type" {...props}></Icon>
