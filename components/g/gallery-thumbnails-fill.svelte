<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q46im1cui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q46im1cui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-thumbnails-fill" {...props}></Icon>
