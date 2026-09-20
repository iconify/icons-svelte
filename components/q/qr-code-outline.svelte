<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xza0rac-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xza0rac-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:qr-code-outline" {...props}></Icon>
