<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn199flym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kn199flym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-arrow-forward" {...props}></Icon>
