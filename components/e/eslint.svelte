<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpre71u6z.css';
import '../../css/i/i19bypv0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lpre71u6z"/><path class="i19bypv0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:eslint" {...props}></Icon>
