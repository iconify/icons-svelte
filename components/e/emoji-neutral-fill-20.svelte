<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9wy74bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h9wy74bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-neutral-fill-20" {...props}></Icon>
