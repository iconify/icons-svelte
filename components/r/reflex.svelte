<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp0xqacie.css';
import '../../css/y/ycdb5-nqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fp0xqacie"/><path class="ycdb5-nqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:reflex" {...props}></Icon>
