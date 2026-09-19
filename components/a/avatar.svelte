<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8nfbhc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t8nfbhc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:avatar" {...props}></Icon>
