<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy99j9bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="cy99j9bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bill-wave" {...props}></Icon>
