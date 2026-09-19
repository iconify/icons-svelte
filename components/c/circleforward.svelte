<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2gi3tfwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i2gi3tfwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleforward" {...props}></Icon>
