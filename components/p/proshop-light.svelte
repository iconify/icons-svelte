<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mino6h8rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mino6h8rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proshop-light" {...props}></Icon>
