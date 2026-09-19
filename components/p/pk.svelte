<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bxvx0cc-x.css';
import '../../css/g/gtaiscbqc.css';
import '../../css/l/lj8bjt19g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bxvx0cc-x"/><path class="gtaiscbqc"/><path class="lj8bjt19g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:pk" {...props}></Icon>
