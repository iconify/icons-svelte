<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1m3t8g2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g1m3t8g2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:infographic" {...props}></Icon>
