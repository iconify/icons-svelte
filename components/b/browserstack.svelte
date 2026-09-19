<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnow--1ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bnow--1ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:browserstack" {...props}></Icon>
