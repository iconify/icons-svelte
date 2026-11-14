<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c9ult2btp.css';
import '../../css/q/qdzi_jzoh.css';
import '../../css/g/ggell_ipy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c9ult2btp"/><path class="qdzi_jzoh"/><path class="ggell_ipy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-block-02" {...props}></Icon>
