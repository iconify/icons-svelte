<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzg7-ybcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qzg7-ybcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pet-paw" {...props}></Icon>
