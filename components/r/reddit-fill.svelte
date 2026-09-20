<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xshk93bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xshk93bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:reddit-fill" {...props}></Icon>
