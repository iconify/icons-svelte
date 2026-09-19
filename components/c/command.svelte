<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2d0jabze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2d0jabze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:command" {...props}></Icon>
