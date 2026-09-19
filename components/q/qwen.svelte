<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fmeovypeb.css';
import '../../css/k/kjeii5b8e.css';
import '../../css/l/lrd4lfbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmeovypeb"/><path class="kjeii5b8e"/><path class="lrd4lfbqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:qwen" {...props}></Icon>
