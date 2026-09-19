<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umx86bbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="umx86bbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:elasticsearch" {...props}></Icon>
