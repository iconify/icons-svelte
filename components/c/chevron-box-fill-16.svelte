<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn881uvep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pn881uvep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-box-fill-16" {...props}></Icon>
