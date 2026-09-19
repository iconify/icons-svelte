<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrlw1ob2d.css';
import '../../css/p/p_titlbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xrlw1ob2d"/><path class="p_titlbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:brokenheart" {...props}></Icon>
