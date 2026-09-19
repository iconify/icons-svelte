<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9-ydhbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h9-ydhbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:consul" {...props}></Icon>
