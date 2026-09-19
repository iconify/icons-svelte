<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og18brbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="og18brbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:npss" {...props}></Icon>
