<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oys82-bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oys82-bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:lwc" {...props}></Icon>
