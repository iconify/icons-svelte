<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jvt7-4buc.css';
import '../../css/b/brnzpbt4j.css';
import '../../css/l/l47aljkcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jvt7-4buc"/><path class="brnzpbt4j"/><path class="l47aljkcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:focus-frame-target-1" {...props}></Icon>
