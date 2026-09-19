<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz464fbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iz464fbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gentoo" {...props}></Icon>
