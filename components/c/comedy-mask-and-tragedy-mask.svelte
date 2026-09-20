<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t85k80b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t85k80b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:comedy-mask-and-tragedy-mask" {...props}></Icon>
