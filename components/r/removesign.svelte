<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdkvtgb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gdkvtgb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:removesign" {...props}></Icon>
