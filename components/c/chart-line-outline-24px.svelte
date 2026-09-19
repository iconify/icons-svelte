<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sx571qbiw.css';
import '../../css/w/w9qq0ybth.css';
import '../../css/g/gfvbhrbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sx571qbiw"/><path clip-rule="evenodd" class="w9qq0ybth"/><path clip-rule="evenodd" class="gfvbhrbka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-line-outline-24px" {...props}></Icon>
