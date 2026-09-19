<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e_shtx8ok.css';
import '../../css/k/kxk1ljbls.css';
import '../../css/e/eko1wqb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="e_shtx8ok"/><path class="kxk1ljbls"/><path class="eko1wqb5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mail-inbox" {...props}></Icon>
