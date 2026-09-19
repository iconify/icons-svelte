<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zik-cdbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zik-cdbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gateway-inclusive-alt" {...props}></Icon>
