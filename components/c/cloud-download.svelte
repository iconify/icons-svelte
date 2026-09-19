<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dah10_0uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1408};
const content = `<path class="dah10_0uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cloud-download" {...props}></Icon>
