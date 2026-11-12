<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w65xx7ela.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w65xx7ela"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:opentofu-wordmark" {...props}></Icon>
