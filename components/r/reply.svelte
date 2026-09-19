<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bha938boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bha938boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:reply" {...props}></Icon>
