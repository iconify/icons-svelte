<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfg210pfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfg210pfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aseprite" {...props}></Icon>
