<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoue5rbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zoue5rbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-playing-tennis" {...props}></Icon>
