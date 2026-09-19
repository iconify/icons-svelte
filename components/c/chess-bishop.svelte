<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj184cc4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="vj184cc4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:chess-bishop" {...props}></Icon>
