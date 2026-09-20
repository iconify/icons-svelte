<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eizdr2f_d.css';
import '../../css/q/qzcstj6ya.css';
import '../../css/v/voplo8xtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eizdr2f_d"/><path class="qzcstj6ya"/><path class="voplo8xtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:flip-reflect-up" {...props}></Icon>
