<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnl716bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nnl716bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-curvy-up-down-1" {...props}></Icon>
