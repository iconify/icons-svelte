<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2zqorujz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2zqorujz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hockey-20" {...props}></Icon>
