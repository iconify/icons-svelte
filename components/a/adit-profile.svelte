<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmxu07dat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tmxu07dat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:adit-profile" {...props}></Icon>
