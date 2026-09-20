<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2w3s1bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e2w3s1bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glide-light" {...props}></Icon>
