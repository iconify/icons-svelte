<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6mfu1bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6mfu1bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:recycle-line" {...props}></Icon>
