<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-i0iub3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":488};
const content = `<path class="p-i0iub3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:robo" {...props}></Icon>
