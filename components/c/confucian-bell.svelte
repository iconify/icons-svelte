<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgu1jru5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgu1jru5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:confucian-bell" {...props}></Icon>
