<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow10mebrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ow10mebrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dash" {...props}></Icon>
