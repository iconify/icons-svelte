<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sleoyfbzy.css';
import '../../css/q/q98k1yb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="sleoyfbzy"/><path clip-rule="evenodd" class="q98k1yb5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:archive-box-x-mark-16-solid" {...props}></Icon>
