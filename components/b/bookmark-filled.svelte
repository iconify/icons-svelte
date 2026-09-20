<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve_3q8ezo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve_3q8ezo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-filled" {...props}></Icon>
