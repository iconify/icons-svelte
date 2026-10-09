<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcyts8bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zcyts8bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-justify-20" {...props}></Icon>
