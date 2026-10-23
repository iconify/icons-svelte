<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o4n78dvgd.css';
import '../../css/c/c05n68bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o4n78dvgd"/><path clip-rule="evenodd" class="c05n68bja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactating-outline-24px" {...props}></Icon>
