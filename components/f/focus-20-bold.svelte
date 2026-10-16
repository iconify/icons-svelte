<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9y9blbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a9y9blbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:focus-20-bold" {...props}></Icon>
