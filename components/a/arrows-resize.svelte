<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv07jkb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv07jkb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-resize" {...props}></Icon>
