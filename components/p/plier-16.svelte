<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru9u8d0sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ru9u8d0sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:plier-16" {...props}></Icon>
