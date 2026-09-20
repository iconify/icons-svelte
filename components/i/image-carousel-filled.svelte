<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-iptellt.css';
import '../../css/o/owrwif8bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-iptellt"/><path class="owrwif8bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-carousel-filled" {...props}></Icon>
