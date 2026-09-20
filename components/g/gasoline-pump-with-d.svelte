<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik7l-vbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ik7l-vbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gasoline-pump-with-d" {...props}></Icon>
