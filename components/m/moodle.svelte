<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq7mhkbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nq7mhkbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:moodle" {...props}></Icon>
