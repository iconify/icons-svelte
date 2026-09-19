<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdzyk0bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pdzyk0bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ros" {...props}></Icon>
