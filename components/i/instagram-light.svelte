<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8edzfyqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8edzfyqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instagram-light" {...props}></Icon>
