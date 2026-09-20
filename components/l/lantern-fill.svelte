<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw-z017na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw-z017na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lantern-fill" {...props}></Icon>
