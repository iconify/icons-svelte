<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt4h9mb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tt4h9mb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-sparkle-stroke-20" {...props}></Icon>
