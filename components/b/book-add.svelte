<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru6q8rbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru6q8rbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:book-add" {...props}></Icon>
