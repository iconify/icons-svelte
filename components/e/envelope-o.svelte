<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8z8v7boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="d8z8v7boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:envelope-o" {...props}></Icon>
