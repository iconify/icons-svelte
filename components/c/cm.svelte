<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jhjpckbvk.css';
import '../../css/e/ezvtrm6iz.css';
import '../../css/m/mg6lwxb5m.css';
import '../../css/q/qmdliab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jhjpckbvk"/><path class="ezvtrm6iz"/><path class="mg6lwxb5m"/><path class="qmdliab1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:cm" {...props}></Icon>
