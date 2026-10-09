<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfcegjvjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zfcegjvjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:play-20-bold" {...props}></Icon>
