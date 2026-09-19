<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2oac6j-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="g2oac6j-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:500px" {...props}></Icon>
