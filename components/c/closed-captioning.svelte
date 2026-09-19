<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfj2f0bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tfj2f0bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:closed-captioning" {...props}></Icon>
