<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/scj6e7j8j.css';
import '../../css/o/obezgrllk.css';
import '../../css/z/zs0uyebvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="scj6e7j8j"/><path class="obezgrllk"/><path clip-rule="evenodd" class="zs0uyebvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:enzyme-outline-24px" {...props}></Icon>
