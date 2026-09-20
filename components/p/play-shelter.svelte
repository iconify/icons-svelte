<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu9ha7bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pu9ha7bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:play-shelter" {...props}></Icon>
