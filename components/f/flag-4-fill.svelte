<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-9jjtbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-9jjtbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-4-fill" {...props}></Icon>
