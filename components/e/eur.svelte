<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te9g8x_4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1408};
const content = `<path class="te9g8x_4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:eur" {...props}></Icon>
