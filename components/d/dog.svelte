<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8se2sqaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n8se2sqaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dog" {...props}></Icon>
