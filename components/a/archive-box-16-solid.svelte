<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ip1gdkmke.css';
import '../../css/y/yx7y574vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ip1gdkmke"/><path clip-rule="evenodd" class="yx7y574vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:archive-box-16-solid" {...props}></Icon>
