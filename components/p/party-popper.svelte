<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv8sgnbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zv8sgnbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:party-popper" {...props}></Icon>
