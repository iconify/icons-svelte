<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh2c8vt1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="bh2c8vt1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rocket" {...props}></Icon>
