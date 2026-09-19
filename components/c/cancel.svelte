<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyjz5_xhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iyjz5_xhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:cancel" {...props}></Icon>
