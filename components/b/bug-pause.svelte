<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co5oh0yvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co5oh0yvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bug-pause" {...props}></Icon>
