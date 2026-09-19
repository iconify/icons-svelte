<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-36k731j.css';
import '../../css/d/d9et4l_ew.css';
import '../../css/j/jwqccdbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j-36k731j"/><path class="d9et4l_ew"/><path class="jwqccdbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:burpsuite-wordmark" {...props}></Icon>
