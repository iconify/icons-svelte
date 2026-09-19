<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn5r7ybyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bn5r7ybyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:circleci" {...props}></Icon>
