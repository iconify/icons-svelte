<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmhy4nbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xmhy4nbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:markdown-outline" {...props}></Icon>
