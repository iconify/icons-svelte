<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsi89wbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zsi89wbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hand-thumbs-up" {...props}></Icon>
