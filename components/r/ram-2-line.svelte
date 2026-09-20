<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yns7smjod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yns7smjod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ram-2-line" {...props}></Icon>
