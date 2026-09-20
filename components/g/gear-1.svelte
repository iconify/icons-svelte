<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gtyn32zwx.css';
import '../../css/c/cjzjnwcsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gtyn32zwx"/><path class="cjzjnwcsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:gear-1" {...props}></Icon>
