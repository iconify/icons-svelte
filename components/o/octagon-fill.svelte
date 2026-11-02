<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm3ioub3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm3ioub3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:octagon-fill" {...props}></Icon>
