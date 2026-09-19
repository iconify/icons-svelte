<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4xh7-bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4xh7-bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:archive" {...props}></Icon>
