<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k6zqa2bdl.css';
import '../../css/g/g0l_0wbda.css';
import '../../css/r/rei6xduai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="k6zqa2bdl"/><path clip-rule="evenodd" class="g0l_0wbda"/><path clip-rule="evenodd" class="rei6xduai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:book-print" {...props}></Icon>
