<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4flyybqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4flyybqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-slash-2-filled" {...props}></Icon>
