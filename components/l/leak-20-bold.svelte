<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b146zkmak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b146zkmak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leak-20-bold" {...props}></Icon>
