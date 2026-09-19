<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfxjh-beo.css';
import '../../css/j/j94shoiso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yfxjh-beo"/><path class="j94shoiso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kubernetes" {...props}></Icon>
