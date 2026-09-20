<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luranhnxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luranhnxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:antenna" {...props}></Icon>
