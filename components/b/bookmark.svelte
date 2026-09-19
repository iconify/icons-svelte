<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-wyp6yfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="j-wyp6yfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:bookmark" {...props}></Icon>
