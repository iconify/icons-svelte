<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0cgdac9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n0cgdac9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:car-fill-12" {...props}></Icon>
