<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npr122_rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="npr122_rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ampersand" {...props}></Icon>
