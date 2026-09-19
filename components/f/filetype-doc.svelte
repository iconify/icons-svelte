<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3l_0fbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t3l_0fbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-doc" {...props}></Icon>
