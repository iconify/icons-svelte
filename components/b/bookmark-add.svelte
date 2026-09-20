<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ebhuqwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8ebhuqwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bookmark-add" {...props}></Icon>
