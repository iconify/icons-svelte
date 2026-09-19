<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgnghdc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zgnghdc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rollup" {...props}></Icon>
