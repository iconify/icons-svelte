<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6z79faub.css';
import '../../css/d/d7sn98bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j6z79faub"/><path class="d7sn98bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:flask-wordmark" {...props}></Icon>
