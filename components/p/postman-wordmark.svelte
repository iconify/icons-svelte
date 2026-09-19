<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x579hjb9j.css';
import '../../css/a/ad8vvnbjm.css';
import '../../css/j/j1dztmbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x579hjb9j"/><path class="ad8vvnbjm"/><path class="j1dztmbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:postman-wordmark" {...props}></Icon>
