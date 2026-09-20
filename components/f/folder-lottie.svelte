<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbbjl8juq.css';
import '../../css/d/dld45g65o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wbbjl8juq"/><path class="dld45g65o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-lottie" {...props}></Icon>
