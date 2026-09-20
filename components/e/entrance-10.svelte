<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c04itccgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="c04itccgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:entrance-10" {...props}></Icon>
