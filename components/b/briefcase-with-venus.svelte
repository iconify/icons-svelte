<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7ck4bbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a7ck4bbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-venus" {...props}></Icon>
