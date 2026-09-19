<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q36q3-bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q36q3-bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:google" {...props}></Icon>
