<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-lvsxb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h-lvsxb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:image-fill-12" {...props}></Icon>
