<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/onx5i2vgi.css';
import '../../css/u/u0ms8pngb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="list-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="onx5i2vgi"/><path class="u0ms8pngb"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:list-outline" {...props}></Icon>
