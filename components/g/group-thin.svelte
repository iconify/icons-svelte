<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efue3gdvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="efue3gdvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:group-thin" {...props}></Icon>
