<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xui0s0b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xui0s0b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gitlab" {...props}></Icon>
