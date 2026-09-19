<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gudce39lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gudce39lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:grafanaloki" {...props}></Icon>
