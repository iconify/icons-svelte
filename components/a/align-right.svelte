<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3kb7_czp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k3kb7_czp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:align-right" {...props}></Icon>
