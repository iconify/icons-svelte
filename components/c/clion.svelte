<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uusi_52_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uusi_52_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:clion" {...props}></Icon>
