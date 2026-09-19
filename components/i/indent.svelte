<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8x7nbbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u8x7nbbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:indent" {...props}></Icon>
