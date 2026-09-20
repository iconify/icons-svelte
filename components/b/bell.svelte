<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h95qwns3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h95qwns3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bell" {...props}></Icon>
