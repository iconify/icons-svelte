<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgcq7ab0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tgcq7ab0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:header-5-20" {...props}></Icon>
