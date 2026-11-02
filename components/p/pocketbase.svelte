<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhq98f3wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lhq98f3wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pocketbase" {...props}></Icon>
