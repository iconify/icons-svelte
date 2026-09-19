<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp7a4ne3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bp7a4ne3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:confluence" {...props}></Icon>
