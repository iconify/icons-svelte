<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuxgncb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1824,"height":1792};
const content = `<path class="wuxgncb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:grav" {...props}></Icon>
