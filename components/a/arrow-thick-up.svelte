<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkmzcznuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zkmzcznuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-thick-up" {...props}></Icon>
