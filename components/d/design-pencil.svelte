<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi780g99c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zi780g99c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-pencil" {...props}></Icon>
