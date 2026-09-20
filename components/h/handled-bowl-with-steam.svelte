<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlfjhsu0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hlfjhsu0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:handled-bowl-with-steam" {...props}></Icon>
