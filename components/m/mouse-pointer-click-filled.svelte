<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3zrck5ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3zrck5ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-pointer-click-filled" {...props}></Icon>
