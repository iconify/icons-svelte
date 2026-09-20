<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fftbt4ikp.css';
import '../../css/z/zuqwdabeh.css';
import '../../css/w/wptgjib0k.css';
import '../../css/j/jo5vtjbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fftbt4ikp"/><path class="zuqwdabeh"/><path class="wptgjib0k"/><path class="jo5vtjbfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-metaphor-burn-money" {...props}></Icon>
