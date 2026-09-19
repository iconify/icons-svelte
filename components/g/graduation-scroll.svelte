<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kddnubb0l.css';
import '../../css/v/v5x384kor.css';
import '../../css/b/bnkzc605v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kddnubb0l"/><path class="v5x384kor"/><path class="bnkzc605v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:graduation-scroll" {...props}></Icon>
