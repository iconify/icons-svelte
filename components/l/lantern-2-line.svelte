<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk7yoq7ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk7yoq7ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lantern-2-line" {...props}></Icon>
