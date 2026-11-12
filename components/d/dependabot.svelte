<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg5zf7b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bg5zf7b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dependabot" {...props}></Icon>
