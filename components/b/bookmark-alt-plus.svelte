<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr6ielglk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr6ielglk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmark-alt-plus" {...props}></Icon>
