<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llvz37kzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="llvz37kzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-key-20" {...props}></Icon>
