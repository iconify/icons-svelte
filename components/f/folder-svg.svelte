<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lszm1acwc.css';
import '../../css/u/u4bkq5bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lszm1acwc"/><path class="u4bkq5bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-svg" {...props}></Icon>
