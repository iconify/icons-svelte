<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz2sgybcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz2sgybcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-desktop" {...props}></Icon>
