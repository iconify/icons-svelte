<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4ztfc8fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":411,"height":512};
const content = `<path class="d4ztfc8fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lolcode" {...props}></Icon>
