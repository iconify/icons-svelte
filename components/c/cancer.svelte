<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw5k4ibut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dw5k4ibut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cancer" {...props}></Icon>
