<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z--xdhb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z--xdhb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:focus-points" {...props}></Icon>
