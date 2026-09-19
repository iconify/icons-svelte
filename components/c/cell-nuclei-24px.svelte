<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/afn5g7bzd.css';
import '../../css/m/md5aejbhd.css';
import '../../css/a/aylzo1b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="afn5g7bzd"/><path clip-rule="evenodd" class="md5aejbhd"/><path clip-rule="evenodd" class="aylzo1b9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cell-nuclei-24px" {...props}></Icon>
