<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr71nbcku.css';
import '../../css/p/p7p46pb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vr71nbcku"/><path class="p7p46pb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:codewars-wordmark" {...props}></Icon>
