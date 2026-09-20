<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/goxedu8-m.css';
import '../../css/q/qtdl2pk3h.css';
import '../../css/n/nnirq57eg.css';
import '../../css/d/daqja6rxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="goxedu8-m"/><path class="qtdl2pk3h"/><path class="nnirq57eg"/><path class="daqja6rxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:donation-charity-donate-box" {...props}></Icon>
