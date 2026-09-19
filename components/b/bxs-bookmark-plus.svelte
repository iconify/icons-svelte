<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6ylgd8-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6ylgd8-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bookmark-plus" {...props}></Icon>
