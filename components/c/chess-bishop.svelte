<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k544t6a1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="k544t6a1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chess-bishop" {...props}></Icon>
