<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hernl_b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hernl_b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:celsius" {...props}></Icon>
