<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plwl6db0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="plwl6db0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:csharp" {...props}></Icon>
