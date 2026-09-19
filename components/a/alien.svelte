<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhai0s2xq.css';
import '../../css/a/agy98qb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lhai0s2xq"/><path class="agy98qb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:alien" {...props}></Icon>
