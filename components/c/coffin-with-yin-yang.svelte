<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pida6145z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pida6145z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-yin-yang" {...props}></Icon>
