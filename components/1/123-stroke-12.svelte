<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwr21lb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lwr21lb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:123-stroke-12" {...props}></Icon>
