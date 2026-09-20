<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw6_m-bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xw6_m-bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:insert-side" {...props}></Icon>
