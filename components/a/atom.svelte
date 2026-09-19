<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfw7oseas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="yfw7oseas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:atom" {...props}></Icon>
