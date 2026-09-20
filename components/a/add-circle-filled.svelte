<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1_6p3b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1_6p3b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:add-circle-filled" {...props}></Icon>
