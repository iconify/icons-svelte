<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/trh1kueif.css';
import '../../css/p/pt_w-kkkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="trh1kueif"/><path class="pt_w-kkkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-right-to-bracket" {...props}></Icon>
