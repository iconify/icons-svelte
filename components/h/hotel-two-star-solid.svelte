<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3nceedcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r3nceedcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-two-star-solid" {...props}></Icon>
