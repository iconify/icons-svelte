<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt6wc-5ul.css';
import '../../css/i/iopdlzu5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zt6wc-5ul"/><path class="iopdlzu5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-magic-rabbit" {...props}></Icon>
