<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9c-be7dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f9c-be7dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-om" {...props}></Icon>
