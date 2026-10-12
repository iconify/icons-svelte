<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb5d57cbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pb5d57cbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:email-stroke-20" {...props}></Icon>
