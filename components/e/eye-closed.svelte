<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2uszoujg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":14};
const content = `<path class="z2uszoujg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:eye-closed" {...props}></Icon>
