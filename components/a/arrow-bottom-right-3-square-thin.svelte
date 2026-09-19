<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdlyf0bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdlyf0bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-3-square-thin" {...props}></Icon>
