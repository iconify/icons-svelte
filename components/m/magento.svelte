<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzqcme19q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzqcme19q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:magento" {...props}></Icon>
