<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac8s-6m3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ac8s-6m3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:reactrouter" {...props}></Icon>
