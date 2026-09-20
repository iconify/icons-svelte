<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-8p8db5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e-8p8db5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:meta" {...props}></Icon>
