<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc8dxpb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rc8dxpb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-right-box" {...props}></Icon>
