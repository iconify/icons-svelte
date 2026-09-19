<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/baoulvu-a.css';
import '../../css/t/t5wmzhbeo.css';
import '../../css/j/jjym_-b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="baoulvu-a"/><path class="t5wmzhbeo"/><path class="jjym_-b0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pneumonia-outline-24px" {...props}></Icon>
