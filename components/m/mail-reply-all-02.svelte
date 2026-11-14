<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/b/bffbfcbff.css';
import '../../css/z/z5y389h1p.css';
import '../../css/g/gjj6jlbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="bffbfcbff"/><path class="z5y389h1p"/><path class="gjj6jlbud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-reply-all-02" {...props}></Icon>
