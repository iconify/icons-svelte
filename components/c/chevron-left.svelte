<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8jcolbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u8jcolbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:chevron-left" {...props}></Icon>
