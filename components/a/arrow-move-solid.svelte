<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrc-9yb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mrc-9yb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-move-solid" {...props}></Icon>
