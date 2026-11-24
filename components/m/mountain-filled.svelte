<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8-88ads.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8-88ads"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mountain-filled" {...props}></Icon>
