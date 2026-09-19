<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs0kbjd4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zs0kbjd4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nano" {...props}></Icon>
