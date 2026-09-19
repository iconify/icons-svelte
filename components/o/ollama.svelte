<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu-l2rb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iu-l2rb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ollama" {...props}></Icon>
