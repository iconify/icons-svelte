<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqd53454f.css';
import '../../css/t/ttzgexr7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lqd53454f"/><path class="ttzgexr7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jetbrains" {...props}></Icon>
