<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9u9qcgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tb9u9qcgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building-circle-exclamation" {...props}></Icon>
