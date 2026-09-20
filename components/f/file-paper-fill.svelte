<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf6rbr4fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6rbr4fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-paper-fill" {...props}></Icon>
