<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7ybh6b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7ybh6b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comments-text-outline" {...props}></Icon>
