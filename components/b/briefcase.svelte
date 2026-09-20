<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2p2wut3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j2p2wut3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:briefcase" {...props}></Icon>
