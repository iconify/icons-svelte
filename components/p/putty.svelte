<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j47_jckem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j47_jckem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:putty" {...props}></Icon>
