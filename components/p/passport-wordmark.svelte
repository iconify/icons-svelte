<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjvowy43g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tjvowy43g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:passport-wordmark" {...props}></Icon>
