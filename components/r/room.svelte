<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f89bh-bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f89bh-bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:room" {...props}></Icon>
