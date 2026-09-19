<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa0jhhyhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oa0jhhyhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:positron" {...props}></Icon>
