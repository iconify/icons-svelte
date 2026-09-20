<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsxgsuraf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsxgsuraf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:at-fill" {...props}></Icon>
