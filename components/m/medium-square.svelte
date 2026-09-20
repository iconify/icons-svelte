<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gt_nya-9k.css';
import '../../css/p/pltokbbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="gt_nya-9k"/><path class="pltokbbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:medium-square" {...props}></Icon>
