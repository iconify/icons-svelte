<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npjkx-b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npjkx-b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-plus-bold" {...props}></Icon>
