<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l21w7pbid.css';
import '../../css/z/zhe6sbcdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l21w7pbid"/><path class="zhe6sbcdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-width-filled" {...props}></Icon>
