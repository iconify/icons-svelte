<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cou-7vbaz.css';
import '../../css/h/hbbd_v5xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="cou-7vbaz"/><path clip-rule="evenodd" class="hbbd_v5xz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-16-solid" {...props}></Icon>
