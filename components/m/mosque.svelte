<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs9zi91gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="cs9zi91gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mosque" {...props}></Icon>
