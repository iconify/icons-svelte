<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/m-yrbu6hq.css';
import '../../css/j/j5vme-6vm.css';
import '../../css/j/ju7fwrb5h.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="m-yrbu6hq"/><path class="j5vme-6vm"/><path class="ju7fwrb5h"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:hourglass-circle" {...props}></Icon>
