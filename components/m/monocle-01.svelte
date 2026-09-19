<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bsc_-kbyb.css';
import '../../css/e/ec1r3sx7z.css';
import '../../css/l/ldv_q5b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsc_-kbyb"/><path class="ec1r3sx7z"/><path class="ldv_q5b1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:monocle-01" {...props}></Icon>
