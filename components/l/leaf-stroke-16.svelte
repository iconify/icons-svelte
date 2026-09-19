<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0eold8jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l0eold8jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:leaf-stroke-16" {...props}></Icon>
