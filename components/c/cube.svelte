<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw0_fkb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pw0_fkb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cube" {...props}></Icon>
