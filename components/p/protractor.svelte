<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvnmchr1u.css';
import '../../css/z/z6avml47a.css';
import '../../css/p/pvttq6b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uvnmchr1u"/><path class="z6avml47a"/><path class="pvttq6b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:protractor" {...props}></Icon>
