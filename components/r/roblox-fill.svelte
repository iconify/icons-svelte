<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z148u-b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z148u-b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:roblox-fill" {...props}></Icon>
